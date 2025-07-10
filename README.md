osTicket - Post-Install Configuration
<p align="center"> <img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/> </p>
Overview
This guide walks through the post-installation configuration of osTicket, an open-source support ticket system. After the core installation, several configuration steps are needed to make the platform fully functional for managing support operations.

📺 Video Demonstration
YouTube: How To Configure osTicket, Post-Installation
(Full walkthrough of the setup and configuration process.)

🧰 Environments and Technologies Used
Microsoft Azure – Virtual Machines / Compute

Remote Desktop Protocol (RDP)

Internet Information Services (IIS) – Web server for osTicket hosting

🖥️ Operating System Used
Windows 10 (21H2)

🎯 Post-Install Configuration Objectives
Configure basic system settings (name, timezone, default email)

Set up Departments, Teams, and Help Topics

Create and assign user Roles and Permissions

Configure SMTP and Email Piping

Enable and test ticket creation and response workflows

🔧 Configuration Steps with Screenshots
1️⃣ System Settings & Preferences
<p align="center"> <img src="https://i.imgur.com/DJmEXEB.png" width="80%" alt="System Settings"/> </p>
Set the help desk name, timezone, system email, and default language preferences under the Admin panel.

2️⃣ Creating Departments & Help Topics
<p align="center"> <img src="https://i.imgur.com/DJmEXEB.png" width="80%" alt="Help Topics and Departments"/> </p>
Departments route tickets to the right support teams. Help Topics allow end users to categorize their requests easily during submission.

3️⃣ Setting User Roles and Agent Access
<p align="center"> <img src="https://i.imgur.com/DJmEXEB.png" width="80%" alt="Agent Roles and Permissions"/> </p>
Roles define access levels, while Teams group agents under specific departments. Permissions can be fine-tuned for agents, managers, or admins.

4️⃣ Configuring Email Settings (SMTP)
<p align="center"> <img src="https://i.imgur.com/DJmEXEB.png" width="80%" alt="Email Configuration"/> </p>
Enable email fetching and ticket replies using SMTP/IMAP settings. osTicket will send notifications to both agents and end users.

5️⃣ Ticket Workflow Test
<p align="center"> <img src="https://i.imgur.com/DJmEXEB.png" width="80%" alt="Ticket Test Screenshot"/> </p>
Submit a test ticket as a user and verify it flows properly through the system—from intake to agent notification to resolution.

✅ Summary
This project helps establish a fully functional osTicket support desk by covering:

Initial system tuning

Organizational structure setup (Departments, Teams)

Email communication integration

Real-world test of ticket lifecycle

These foundational steps are essential before deploying osTicket in a production environment.


