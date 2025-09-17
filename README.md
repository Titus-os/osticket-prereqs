<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Prerequisites and Installation</h1>
This tutorial outlines the prerequisites and installation of the open-source help desk ticketing system osTicket.<br />


<h2>Video Demonstration</h2>

- ### [YouTube: How To Install osTicket with Prerequisites](https://www.youtube.com)

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>List of Prerequisites</h2>

- Installed / Enabled IIS in Windows WITH CGI
- Installed PHP and Registered PHP from within IIS
- Installed MySQL and Created the osTicket Database
- Copied and Configured osTicket Files in IIS
- Enabled PHP Extensions and Finalized osTicket Installation in Browser



<h2>Installation Steps</h2>

<p>
<img width="1345" height="852" alt="image" src="https://github.com/user-attachments/assets/8c1bef1f-724c-4f87-9b69-c41ed6870d13" />
</p>
<p>
Enabling Internet Information Services (IIS) with CGI (Common Gateway Interface) is critical because osTicket, a web-based application, requires a web server to host its files and process dynamic content. CGI support is necessary for PHP to execute properly within IIS, allowing osTicket’s PHP-based scripts to run and serve the help desk interface.

</p>
<br />

<p>
<img width="1378" height="954" alt="image" src="https://github.com/user-attachments/assets/61d81cde-35de-4502-90a5-f898dcb6af11" />
<img width="1450" height="757" alt="image" src="https://github.com/user-attachments/assets/4ac32222-e512-42a1-8936-bb4101aa6788" />
</p>
<p>
Installing PHP (via the PHP 7.3.8 files into C:\PHP) and registering it in IIS using PHP Manager is essential because osTicket is built on PHP. Registering php-cgi.exe ensures IIS can process PHP scripts, enabling the core functionality of osTicket’s web interface and backend logic.

</p>
<br />

<p>
<img width="1163" height="653" alt="image" src="https://github.com/user-attachments/assets/ec5a0a95-fa92-4a0f-abfe-7f90633a985f" />

</p>
<p>
Enabling the PHP extensions (php_imap.dll, php_intl.dll, php_opcache.dll) in PHP Manager and completing the osTicket setup through the browser (configuring database and help desk settings) are crucial for enabling full functionality. These extensions support email integration, internationalization, and performance optimization, while the browser setup finalizes the database connection and initializes the help desk.
</p>
<br />
