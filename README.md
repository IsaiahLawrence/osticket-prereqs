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

- We'll then install PHP manager, rewrite module, C++redist file, MySQL. All those files will be found on osTicket page.

- When we download our PHP 7.3.8 we need to make a new folder in our C drive and name it PHP we'll then unzip the contents into that folder.

<p> Once MYSQL is downloaded set it up using the Typical option then Standard Configuration (https://github.com/IsaiahLawrence/osticket-prereqs/assets/152194351/46b40c3b-6167-4025-9508-0d552bd79a4a) 
Set your password and continue on. SQL is needed to use osTicket to store all the data such as users,tickets,etc..

Once you've set up SQL we need to register PHP from within IIS, to do so we run IIS as admin do this by pressing the window key typing IIS rightclick IIS and run as admin. You should see this window ![image](https://github.com/IsaiahLawrence/osticket-prereqs/assets/152194351/502ee916-9afb-44eb-8454-702c75de4ea1) Click PHP Manager and Register new PHP version inside our PHP folder(the folder we created earlier on our C drive) we should have CGI application in there. Restart IIS and now we can install osTicket.

</p> Once we download osTicket it'll be in a zipfile we want to click into it and take that upload folder copy and extract it to our wwwroot folder. This is found in C drive>inetpub>wwwroot 
<p>![image](https://github.com/IsaiahLawrence/osticket-prereqs/assets/152194351/cd6e578e-fa82-4192-9e28-0b92ef0de01d) should look like so. Rename that upload folder to osTicket. Then restart IIS. From the left drop down go to sites, deafault web site, osTicket ![image](https://github.com/IsaiahLawrence/osticket-prereqs/assets/152194351/5abd80cd-0f3d-4b8d-8e93-f3772432ca66) on the right side you'll see Browse*.80.
  
  When you click that it should bring you to the osTicket installer. ![image](https://github.com/IsaiahLawrence/osticket-prereqs/assets/152194351/03d0eb69-561f-48eb-8d7c-17cb47858555)
</p>

<p>  You'll notice that the website reccomends we turn on some features, to turn those on we'll go back to IIS and go into our PHP manager scroll down to PHP Extensions click enable or disable extensions and we'll
  enable php_imap.dll
  enable php_intl.dll
  enable php_opcache.dll
Once that's complete refresh the webpage. Before pressing continue go to your osTicket folder>include and find a file named "ost-sammpleconfig.php" rename this file to "ost-config.php" if you don't do this step when you hit continue you'll get a Configuration file missing page! Looks like this;  
![image](https://github.com/IsaiahLawrence/osticket-prereqs/assets/152194351/ba1d16e9-7f31-442c-ae09-05d84a6d1720)



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
