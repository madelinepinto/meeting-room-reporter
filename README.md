# **Meeting Room Reporter**
This project was created in collaboration with __Piotr Pralat__ and __Sid Pathak__ as part of the __BCI Invent Hackathon__.

## Overview
Our goal with this project was to make a user-friendly and cohesive meeting booking system with an accurate reporting tool. Through our platform, employees can use an interactive organizational chart to select members for their meetings, and use the visual directory to find available room bookings that meet their business needs.

## Technology Used
* __PowerBI__ to visualize the room usage data and the organizaional structure.  
* __Power Automate__ to send the Outlook Calendar Invite to the selected employees.  
* __SQL Servers__ to host databases for room usage, room ammenities, and employee schedules.  

## How It Works
### Room Booking Feature
1. The user selects the people they want invited to the meeting by using the synced slicer on the left panel of the Organizational Chart. They can also select the room features (i.e. coffee, HDMI, etc) they want included in the room.
![image](https://github.com/user-attachments/assets/55976db0-8306-4c1f-ba7f-85a0f43bcb3c)
2. The user clicks 'Book Meeting' and they are redirected to the Visual Directory Page. In this page, they can see the room availability and select the start and end time of their meeting.
![image](https://github.com/user-attachments/assets/e67372ff-4054-4775-a456-3768b3e6c593)
3. The user confirms their selection by clicking 'Book Meeting' again, and a Power Automate Flow is triggered to send the Outlook Calendar Event.  
![image](https://github.com/user-attachments/assets/5cf77ca4-9b7a-4d33-b5cf-156e9459d344)
4. Once the meeting is accepted, the SQL databases for room bookings are updated and refreshed.  

### Reporting Feature
1. The user selects the time period that they would like to view and the metric they would like visualized. The data can be represented in a Bar Graph or a Line Graph.
![image](https://github.com/user-attachments/assets/2e6a96c7-9d25-462f-967b-6430190e84f3)
2. The user can click on the arrow in the bottom right corner to view a detailed room usage report.
![image](https://github.com/user-attachments/assets/655b44e2-e174-43c8-8a45-5f0cee72bf91)

## What I learned
The objective of this hackathon was to promote development through Microsoft's **Power Platform**, and so the only tools we were able to use were **PowerBI, Power Automate, Power Apps, and SQL**. This was one of my first projects using PowerBI, so I learned how to visualize data with buttons, synced slicers, pages, and more! Due to the restrictions of the Hackathon environment, I learned how to approach problems with a different mindset in order to achieve the product we desired. I also learned about the significance of **security and confidentiality**. In order to protect people's privacy, we created fake room bookings and meeting data. In production, we would use connectors to pull from real time databases. 

Thank you to all of the organizers and staff members who organized this inaugral hackathon. I am grateful to have worked with an amazing team in a collaborative and innovative environment, and I look forward to completing more hackathons in the future!

