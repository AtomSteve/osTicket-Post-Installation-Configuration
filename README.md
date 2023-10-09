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

- Windows 10</b> (21H2)

<h2>Post-Install Configuration Objectives</h2>

- Configure Roles
- Configure Departments
- Configure Teams
- Allow Ticket Creation
- Configure Teams/Workers
- configure Users
- Configure SLA
- Configure Help Topics
  
<h2>Configuration Steps</h2>

<p>

Log into osTicket with your Administrator credentials.  First thing we are going to configure is Roles.  Got to Admin Panel -> Agents -> Roles, then proceed to make a role called "supreme Admin

</p>
<p>

![image](https://github.com/AtomSteve/osTicket-Post-Installation-Configuration/assets/147112183/ab06a3a8-8aac-4fb0-a76f-257382c4a527)![image](https://github.com/AtomSteve/osTicket-Post-Installation-Configuration/assets/147112183/26eba479-ee00-4aa2-b526-aff55779e31b)



</p>
<br />

<p>
now go to Admin Panel -> Agents -> Departents -> press add team, and create 
  -Level support
  -Leve2 support
</p>
<p>

![image](https://github.com/AtomSteve/osTicket-Post-Installation-Configuration/assets/147112183/22da4f4e-69dd-4648-9395-8232a9a37386)


</p>
<br />

After creating the support departments, we need to allow anyone to create tickets.  Go to Admin Panel -> Settings -> User -> Make sure the "Registration Required" box is left unchecked
<p>

![image](https://github.com/AtomSteve/osTicket-Post-Installation-Configuration/assets/147112183/ae7835da-eeae-4f41-82bd-a3d5040a0588)



</p>
<p>

Next we will creat some Agents.  Click on Admin Panel -> Agents -> Add New.  Jane and John (These are just Examples)

</p>
<p>

![image](https://github.com/AtomSteve/osTicket-Post-Installation-Configuration/assets/147112183/b11bd4bb-e6fd-4cc3-bf19-65d2793bd0e2)


