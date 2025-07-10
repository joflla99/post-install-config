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
<img width="686" height="386" alt="image" src="https://github.com/user-attachments/assets/3b08fda2-ea53-43dd-8573-3211c8813fb5" />

Set the help desk name, timezone, system email, and default language preferences under the Admin panel.

2️⃣ Creating Departments & Help Topics
<img width="2560" height="1278" alt="image" src="https://github.com/user-attachments/assets/ce78ad8d-0258-4b0b-9fac-0947b50acdcb" />

Departments route tickets to the right support teams. Help Topics allow end users to categorize their requests easily during submission.

3️⃣ Setting User Roles and Agent Access

<img width="571" height="259" alt="image" src="https://github.com/user-attachments/assets/bae9284f-4fb4-473d-90c8-027b5ff7449e" />

Roles define access levels, while Teams group agents under specific departments. Permissions can be fine-tuned for agents, managers, or admins.

4️⃣ Configuring Email Settings (SMTP)

<img width="712" height="720" alt="image" src="https://github.com/user-attachments/assets/5df494b1-5dcb-4c47-9fb3-ce95322efb30" />

Enable email fetching and ticket replies using SMTP/IMAP settings. osTicket will send notifications to both agents and end users.

5️⃣ Ticket Workflow Test
Submit a test ticket as a user and verify it flows properly through the system—from intake to agent notification to resolution.

✅ Summary
This project helps establish a fully functional osTicket support desk by covering:

Initial system tuning

Organizational structure setup (Departments, Teams)

Email communication integration

Real-world test of ticket lifecycle

These foundational steps are essential before deploying osTicket in a production environment.


