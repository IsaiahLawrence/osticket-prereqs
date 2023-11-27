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

- Windows 10</b> (22H2)

<h2>List of Prerequisites</h2>

- Install and enable IIS (Internet Information Services) this allows the computer to provide the osTicket website. *IIS is found in control panel under programs.
- ![image](https://github.com/IsaiahLawrence/osticket-prereqs/assets/152194351/1f2e2092-1793-4d90-93ac-e313bed86466) You'll also turn on CGI found in the World Wide Web Services>Application Development Features>CGI
- After Installing IIS to ensure you've installed it correctly enter your loopback address(127.0.0.1) into the URL you should see a webpage like so; ![image](https://github.com/IsaiahLawrence/osticket-prereqs/assets/152194351/4a2ff9a8-9f73-4d6f-bf1b-8f213dbd423d) 

- We'll then install PHP manager, rewrirte module, C++redist file, MySQL. All those files will be found on osTicket page.

<p> Once MYSQL is downloaded set it up using the Typical option then Standard Configuration ![image](https://github.com/IsaiahLawrence/osticket-prereqs/assets/152194351/46b40c3b-6167-4025-9508-0d552bd79a4a) 
Set your password and continue on. SQL is needed to use osTicket to store all the data such as users,tickets,etc..

Once you've set up SQL we need to register PHP from within IIS, to do so we run IIS as admin do this by pressing the window key typing ISS rightclick ISS and run as admin. You should see this window ![image](https://github.com/IsaiahLawrence/osticket-prereqs/assets/152194351/502ee916-9afb-44eb-8454-702c75de4ea1)

</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />
