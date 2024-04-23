# post-install-config
<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post-Install Configuration</h1>

This project will outline how to effectively set up and optimize a newly installed OS Ticket system.<br />



<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Computer)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10 (4 vCPUs) </b>

<h2>Post-Install Configuration Objectives</h2>

- Configuration of General Settings to include:
   - Roles
   - Departments
   - Teams
   - Agents
   - Users
    
- Configuration of Tickets to include:
   - Service Level Agreement(SLA) Severity Plans
   - Creation of addition Help Topic fields


<h2>Configuration Steps</h2>

<p>
<b>1. Configuration of Roles. </b>
  <p></p>

 - Navigate to:
   - Admin Panel ->
   - Agents ->
   - Roles ->
   - Add New Role
  
<img src= "https://i.imgur.com/sXgnD5V.png"/>
<p>

 - Tabs to fill:
    - Definition: Defines title (Example: Supreme Admin)
    - Permissions: Specify actions and functionalities allowed
    - Ticket: Permissions to create, edit, delete, close, reopen, and view tickets
    - Task: Permissions to create, edit, delete, and view tasks
    - Knowledge Base:  Control access and management of organization's knowledge base

  <img src= "https://i.imgur.com/6YT9GhV.png" height="60%" width="60%"/>
  
  <img src= "https://i.imgur.com/3RiZvjr.png" height="60%" width="60%"/>

  <img src= "https://i.imgur.com/Gs4Sea2.png" height="60%" width="60%"/>

 - Click "Add Role"
<p>
<b>2. Configuration of Departments </b>
  <p></p>

 - Navigate to:
    - Admin Panel ->
    - Agents ->
    - Departments ->
    - Add New Department

<img src= "https://i.imgur.com/CHgP87p.png" />
<p>

 - Tabs to fill:
    - Settings: Define department specifics (name, email, description) and define SLA specifics for department
    - Access: Define agents in department, define permissions of agents in department, and configure ticket assignment and access.

<img src="https://i.imgur.com/G9M8x2r.png" height="60%" width="60%"/>

 - Click "Create Department"

<p>
<b>3. Configuration of Teams </b>
  <p></p>

 - Navigate to:
    - Admin Panel ->
    - Agents ->
    - Teams ->
    - Add New Team
<p>
<img src= "https://i.imgur.com/XzffxAj.png"/>
  <p></p>
  
 - Tabs to fill:
    - Team: Define team name, assign team to a department, and assign manager
    - Members: Add or remove members, define permissions of members, and configure ticket assignmnet and access
<p></p>
<img src= "https://i.imgur.com/VDzNJHO.png" height="60%" width="60%"/>
<img src= "https://i.imgur.com/FpVaxTn.png" height="60%" width="60%"/>
 - Click "Create Team"
</p>
<b>4. Configuration of Agents </b>
  <p></p>

 - Navigate to:
    - Admin Panel ->
    - Agents ->
    - Agents ->
    - Add New Agent
<p>
<img src= "https://i.imgur.com/9SuxEma.png"/>
  <p></p>
  
 - Tabs to fill:
    - Account: Set agents full name, username, password, and email 

<img src= "https://i.imgur.com/FxjZSpG.png" height="60%" width="60%"/>

 - Access: Assign department and specify role
<img src= "https://i.imgur.com/zxH9Sw3.png" height="60%" width="60%"/>

 - Permissions: Set ticket, task, knowledge base, and other permissions as neccessary 

<img src= "https://i.imgur.com/KgTgjmh.png" height="60%" width="60%"/>

 - Teams: Add or remove agent from teams
    
<img src="https://i.imgur.com/I6gdu5H.png" height="60%" width="60%"/>
<p></p>

 - Click "Create"
 
<p>
<b>5. Configuration of Users </b>
  <p></p>

 - Navigate to:
    - Agent Panel ->
    - Users ->
    - Add New Users
<p>
<img src= "https://i.imgur.com/03E31FI.png"/>
  <p></p>
  
 - Fill in users email, full name, and phone number
 - Click "Add User"

<img src= "https://i.imgur.com/jEeyIMf.png" height="60%" width="60%"/>
<p></p>
<b>6. Configuration of SLA </b>
  <p></p>

 - Navigate to:
    - Admin Panel ->
    - Manage ->
    - SLA ->
    - Add New SLA Plan

<img src= "https://i.imgur.com/PV0TNSg.png" />
<p>

 - Tabs to fill:
    - Name (Example Sev A)
    - Status: Active or disabled
    - Grace Period: Define how long tickets in this plan need to be completed
    - Schedule: Define hours of operation for this ticket plan (Example: 24/7 or normal business hours)

<img src="https://i.imgur.com/FNtvxAx.png" height="60%" width="60%"/>

 - Click "Add Plan"

<p>
<b>7. Configuration of Help Topics </b>
  <p></p>

 - Navigate to:
    - Admin Panel ->
    - Manage ->
    - Help Topics ->
    - Add New Help Topic
<p>

 - Tabs to fill:
    - Help Topic Information:  Topic title, status, define access to public or internal, and define parent topic

<img src= "https://i.imgur.com/qpKKl6D.png" height="60%" width="60%"/>

 - New Ticket Options: Define further parameters such as routing ticket to specific departments and configure auto-responses
 - Forms: Customize ticket form by adding custom fields to gain more information from users
 - Click "Add Plan"

<img src= "https://i.imgur.com/mqD1svQ.png" height="60%" width="60%"/>

<b> You have now completed the Post Configuration of OS Ticket System<b/>
