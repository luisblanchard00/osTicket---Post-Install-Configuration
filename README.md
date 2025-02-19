<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post-Install Configuration</h1>
This tutorial outlines the post-install configuration of the open-source help desk ticketing system osTicket.<br />


<h2>Video Demonstration</h2>

- ### [YouTube: How To Configure osTicket, post-installation](https://www.youtube.com)

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Post-Install Configuration Objectives</h2>

- Configure User Roles, Departments, and Teams
- Allow Ticket Creation and Configure User Registration
- Configure Agents and Users
- Set Up Service Level Agreements (SLAs)
- Configure Help Topics for Ticket Creation

<h2>Configuration Steps</h2>

![image](https://github.com/user-attachments/assets/19a69cdf-7942-4b51-b194-ece797eb80c2)


Configure User Roles, Departments, and Teams
  - Roles: Set up different roles such as Supreme Admin to group users based on permissions (Admin Panel → Agents → Roles).
  - Departments: Organize ticket visibility by configuring departments like Help Desk, SysAdmins, and Networking (Admin Panel → Agents → Departments).
  - Teams: Create teams by grouping agents from different departments (Admin Panel → Agents → Teams).
<br />

![image](https://github.com/user-attachments/assets/20245765-c69b-4188-94ad-3ead4dcaa4b0)

Configure Agents, Users, and Ticket Creation Settings
  - Agents: Add agents (workers) and assign them to appropriate departments (Admin Panel → Agents → Add New).
  - Users: Add customers (users) who will submit tickets (Agent Panel → Users → Add New).
  - Ticket Creation: Control whether users can create tickets without registering, and configure the requirement for user registration and login to submit a ticket (Admin Panel → Settings → User Settings).
<br />

![image](https://github.com/user-attachments/assets/07233261-b636-4648-9d58-7a8a762b1d31)

Configure SLAs and Help Topics
  - SLAs: Set up Service Level Agreements (SLAs) with different severity levels and define grace periods and schedules for each severity (Admin Panel → Manage → SLA).
  - Help Topics: Set up predefined topics that users can select when creating tickets, such as Business Critical Outage, Equipment Request, and others (Admin Panel → Manage → Help Topics).
<br />
