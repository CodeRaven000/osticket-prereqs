<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Prerequisites and Installation</h1>
This tutorial outlines the prerequisites and installation of osTicket the open-source help desk ticketing system.<br />


</br><h2>Environments & Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (22H2)

<h2>List of Prerequisites</h2>

- Create a virtual machine
- Download PHP Manager & MySQL Server
- Install osTicket
</br>
<h2>Installing osTicket</h2>

</br><p>
<img src="https://i.imgur.com/cLwE0iI.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

<p>
<img src="https://i.imgur.com/EgkbdFV.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Create a virtual machine and use remote desktop connection to login. Download the PHP Manager and MySQL Server. After downloading PHP Manager credentials need to be set up. Go to <b>standard configuration</b> --> <b>next</b> --> <b>create a root password</b> --> <b>next</b> --> <b>execute</b>. In the search bar type IIS right-click then select run as administrator. Double click register new PHP version - browse to find the folder where the PHP files have been extracted and stored. After registering PHP restart IIS.  
</p>
<br />
<p>
<img src="https://i.imgur.com/n1w8Q2y.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Download osTicket. Extract and copy the folder then upload it to the wwwroot folder and rename the folder osTicket.  
</p>
<br />
<p>
<img src="https://i.imgur.com/zV9Wcfb.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

<p>
<img src="https://i.imgur.com/1ynJzOZ.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

<p>
<img src="https://i.imgur.com/1mXSCCA.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Enable the PHP extensions for osTicket. osTicket is now successfully installed! 
</p>
<br />
<p>
<img src="https://i.imgur.com/ZowQ0y6.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

<p>
<img src="https://i.imgur.com/mcWcI4Y.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

