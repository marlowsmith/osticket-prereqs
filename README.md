<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Prerequisites and Installation</h1>
This tutorial outlines the prerequisites and installation of the open-source help desk ticketing system osTicket.<br />




<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>List of Prerequisites</h2>

- Set up process 
- Setting up Windows 10 as a Virtual Machine
- Enabling Internet Information Services 
- osTicket installed
- Extensions Enabled! 

<h2>Overview </h2>

![image](https://github.com/user-attachments/assets/f108c5a6-f5dd-4267-9a4e-5e52127653c0)



<p>
</p>
<p>
Here, you will see the overall setup of my environment to create osTicket. I used Microsoft Azure to build the environment. First, I started a subscription to Microsoft Azure. Then, I started with the creation of the resource group. Next, I built a virtual machine and set up all the requirements to install the osTicket service. Finally, installed osTicket itself on the virtual machine.
</p>
<br />

![image](https://github.com/user-attachments/assets/158b046f-decb-4c73-816b-8a4e11351d42)

<p>
</p>
<p>
I’m creating the virtual machine using Microsoft Azure. My virtual machine is Windows 10. I’m making sure the machine I’m setting up is powerful enough to run the software. I’m naming the machine, setting up usernames and passwords, and getting everything ready to log in to the virtual machine.
</p>
<br />

![image](https://github.com/user-attachments/assets/2b8045de-92d7-43f4-aa6a-d24090635349)

<p>
</p>
<p>
Inside the virtual machine, I’m installing the web server by enabling IIS (Internet Information Services) and CGI, which is a dependency that osTicket needs for part of the web server.
</p>
<br />

![image](https://github.com/user-attachments/assets/5035955d-eedd-411c-9608-1b7e31462f24)

<p>
</p>
<p>
I installed PHP Manager for IIS. PHP is a backend web server language which osTicket needs for it to run. I installed MySQL, which is used for data storage and retrieval. It works on the backend for osTicket to work properly. I’ve succeeded in loading into the osTicket site, but I still have a few more steps to get it configured properly. 
</p>
<br />

![image](https://github.com/user-attachments/assets/c8b12130-4837-43fc-8071-90971e1fb77d)

<p>
</p>
<p>
Loaded into IIS to make configurations. Inside IIS, I enabled the PHP extensions that were needed. I assigned permissions for osTicket to make changes on the backend. I created a helpdesk name and admin user. I installed HeidiSQL. This allows us to make a connection to our database to continue to configure our setup. After opening HeidiSQL, I set up MySQL database, username, and password. All extensions are enabled!
</p>
<br />
