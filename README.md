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

- Using Azure create the Resource Group (RG) and VM to deploy the environment of osTicket
- Enable Internet Information Systems (IIS) in Windows 
- Download all installation files
- Configure osTicket
- Create the osTicket database in Heidi and login to osTicket

<h2>Installation Steps</h2>

<p>
<img src="https://github.com/Beth-Agbassekou/osticket-prereqs/assets/148320585/15a08efe-fe48-4fec-87da-ddf836be1bd6" alt="osTicket RG">
<img width="1440" alt="VM" src="https://github.com/Beth-Agbassekou/osticket-prereqs/assets/148320585/c53b9f42-16d9-43f2-bc06-f43d966a275b">



<p>
The first step was creating a resource group and a VM in Microsoft Azure. Once that was done I copied the address of the VM and logged in to the VM via Microsoft remote desktop. </p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img width="1440" alt="IIS" src="https://github.com/Beth-Agbassekou/osticket-prereqs/assets/148320585/52afa628-9dbd-40c2-bc36-cb50e71ccdd1">
<img width="1440" alt="IIS PHP" src="https://github.com/Beth-Agbassekou/osticket-prereqs/assets/148320585/34b3c34d-becf-4092-b048-cb49d1046324">
<img width="1440" alt="PHP Settings" src="https://github.com/Beth-Agbassekou/osticket-prereqs/assets/148320585/8cfaf479-cc42-4b95-a21f-149f17e09282">
<img width="1440" alt="PHP Extentions" src="https://github.com/Beth-Agbassekou/osticket-prereqs/assets/148320585/93c67cba-cbb7-4e60-9bcc-a011000d3a6b">
<img width="1440" alt="Heidi DB" src="https://github.com/Beth-Agbassekou/osticket-prereqs/assets/148320585/dd56138f-39de-4532-8a59-1fc734430b4d">


</p>
<p>
Once I was connected to the VM I enabled IIS, PHP, and I added a Rewrite Module. I used several installation files including a mySQL file, a Heidi file, and several exe files. Once the files were installed except for Heidi I started configuring osTicket. Then I connected Heidi to osTicket so it had a database to connect to. Once Heidi was connected I launched osTicket with The database I created in Heidi. </p>
<br />

<p>
<img width="1440" alt="OsTicket pre-setup page" src="https://github.com/Beth-Agbassekou/osticket-prereqs/assets/148320585/575c33ed-a2bb-45d8-a699-af5e1f9fdaf6">
<img width="1440" alt="osTicket login after install" src="https://github.com/Beth-Agbassekou/osticket-prereqs/assets/148320585/f686ee19-a76a-466e-8771-209bd41fb048">
  
</p>
<p>
Above are examples of what my pages looked like plus a page after I logged in to osTicket on my computer after installing the necessary files.</p>
<br /># osticket-prereqs
