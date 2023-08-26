<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post-Install Configuration</h1>
This tutorial outlines the post-install configuration of the open-source help desk ticketing system osTicket.<br />

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (22H2)

<h2>Post-Install Configuration Objectives</h2>

- Item 1
- Item 2
- Item 3
- Item 4
- Item 5

<h2>Configuration Steps</h2>

1. Add a new role for the Admin. Admin Panel > Agents > Roles.
   
![01_createrole_admin](https://github.com/JustinHawks/osticket-post-install-config/assets/88342524/fe725821-5877-47b0-a075-46d96502aa30)

2. Enable permissions for the Admin.
   
![02_admin_permissions_all](https://github.com/JustinHawks/osticket-post-install-config/assets/88342524/0356e09f-71fd-4bf0-a9ed-f1181b09090a)

3. Add a department called System Administrators. Admin Panel > Agents > Departments.

![03_sysadmindept](https://github.com/JustinHawks/osticket-post-install-config/assets/88342524/3e3dc2d0-a711-416e-815a-2fa9aa11d679)
![04_departments](https://github.com/JustinHawks/osticket-post-install-config/assets/88342524/e59df509-7937-4541-812d-a82326968580)

4. Add new teams called "Level I Support" and "Level II Support". Admin Panel > Agents > Teams.

![05_teams](https://github.com/JustinHawks/osticket-post-install-config/assets/88342524/139b6e53-8fd7-4553-a846-262287f11944)

5. Allow anyone (users) in the organization to create tickets. Admin Panel > Settings > User Settings. Un-check "Registration Required: Require registration and login to create tickets".
    
![06_allowanyone_createtickets](https://github.com/JustinHawks/osticket-post-install-config/assets/88342524/df14729b-e162-4653-a524-eac079157401)

6. Add new Agents (Help Desk Professionals) who will respond to tickets. Start with adding an Agent with Admin permissions. Admin Panel > Agents - Add New. Enter credentials for the Agent's name, email address, username, and password.
   
![07_newagent](https://github.com/JustinHawks/osticket-post-install-config/assets/88342524/75a612d9-bd4c-4c1c-89a4-39f01d815cf5)
![08_setagentpw](https://github.com/JustinHawks/osticket-post-install-config/assets/88342524/2b847ac8-8da5-4403-ad04-919ac42a0f8c)

7. Asign the Admin Agent to the System Administrators Department.
![09_agentaccess](https://github.com/JustinHawks/osticket-post-install-config/assets/88342524/8682cd9e-025f-44a3-a972-9db12864fd10)

8. Repeat steps 6 - 7 to create Help Desk Agents who will work under the Admins. Assign them to the teams called "Level I Support" and "Level II Support" that you created in step-4.
   
![10_agentteams](https://github.com/JustinHawks/osticket-post-install-config/assets/88342524/e334d027-cecb-4dfc-9c05-6b242f7b12bb)
![11_newagents](https://github.com/JustinHawks/osticket-post-install-config/assets/88342524/1edd8a2a-7293-4efd-b8e5-ddfe73bd8643)

9. Create new SLA's (Service Level Agreements). Admin Panel > Manage > SLA > add new SLA. Set up Sev-A (1 hour, 24/7). Set up Sev-B (4 hours, 24/7). Set up Sev-C (8 hours, business hours).

![12_newSLA](https://github.com/JustinHawks/osticket-post-install-config/assets/88342524/1da0bee0-8932-496f-9792-16ba93128926)
![15_SLAs](https://github.com/JustinHawks/osticket-post-install-config/assets/88342524/3b7ecc16-75b6-4104-a5d3-42492781ce1e)

10. Create new users (ie. employees of an organization or students of a university). Agent Panel > Users > Add New. Enter the user's email address and username.
![12_newusers](https://github.com/JustinHawks/osticket-post-install-config/assets/88342524/4993a8ec-84b9-4a0e-9bef-1773d50d4145)
![13_newusers](https://github.com/JustinHawks/osticket-post-install-config/assets/88342524/4e387882-a131-417d-bc22-8edc097f975b)

11. Create new help topics. Users can categorize their troubleshooting issues with help topics so Agents can better serve users. Admin Panel > Manage > Help Topics.

![16_newhelptopic](https://github.com/JustinHawks/osticket-post-install-config/assets/88342524/dc703bb6-cc76-4529-9376-7fd89e0a3e6e)
![17_helptopics](https://github.com/JustinHawks/osticket-post-install-config/assets/88342524/3d220369-5864-45ef-a43a-eb68fce41a7c)

