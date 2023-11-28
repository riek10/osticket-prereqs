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

- PHP Manager for IIS
- Rewrite Module
- PHP 7.3.8
- Microsoft Visual C++
- MySQL

<h2>Installation Steps</h2>

<p>
<img src="https://github.com/riek10/osticket-prereqs/assets/113129662/64379c74-f926-4689-92ab-1057f7364ddd" height="80%" width="80%"/>
</p>
<p>
First I began by downloading PHP Manager for IIS which is a graphical tool that allows the installation and management of different PHP versions on a windows server. It can enable and disable different PHP extensions and also configure different settings.
</p>
<br />

<p>
<img src="https://github.com/riek10/osticket-prereqs/assets/113129662/fb4747bc-46c8-4033-a77c-c6d637e88840" height="80%" width="80%"/>
</p>
<p>
Pictured above i installed Rewrite Module which is used to change complex web addresses to consistent memorable url's. This will help with opening OsTicket on the browser once the full installaiton/setup is complete.
</p>
<br />

<p>
<img src="https://github.com/riek10/osticket-prereqs/assets/113129662/bc7b93c9-ea6e-49b8-beb4-8ce8b82aabac" height="80%" width="80%"/>
</p>
<p>
I installed MySQL Server for data warehousing in order to store and manage users in a more efficient way for OsTicket. Its a very flexible and easy to manage programming environment. In the next couple of steps i setup MySQL's root user login credentials for when the complete installation of OsTicket is complete.
</p>
<br />

<p>
  <img src="https://github.com/riek10/osticket-prereqs/assets/113129662/8dd3f98c-c12c-41a8-bf70-3c73b5167671" height="80%" width="80%"/>
</p>
<p>
  In this next step i'm registering the PHP-CGI file i downloaded/extracted to the newly created PHP folder in the C: drive.Then i will proceed by downloading OsTicket which is basically just the files for the GUI(Graphical User Interface).
</p>

<p>
  <img src="https://github.com/riek10/osticket-prereqs/assets/113129662/745b38fc-1d42-48c1-b7ca-5637a4507020" height="80%" width="80%"/>
</p>
<p>
  After properly downloading and cofiguring all the files i now have the OsTicket installer loaded on my web browser through the localhost as pictured above.Next ill be configuring all of the proper extentions to assure that OsTicket runs properly.
</p>
