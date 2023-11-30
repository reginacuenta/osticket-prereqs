<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Prerequisites and Installation</h1>
This tutorial outlines the prerequisites and installation of the open-source help desk ticketing system osTicket.<br />


<h2>Video Demonstration</h2>

- ### [YouTube: How To Install osTicket with Prerequisites](https://youtu.be/qZ_kH9ZL5uI)

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>List of Prerequisites</h2>

- Create a Virtual Machine in Azure
- Enable IIS in Windows with CGI and Commin HTTP Features and IIS Management Console
- Install PHP Manager for IIS
- Install the Rewrite Module
- Create the directory for C:\PHP
- Download PHP 7.3.8
- Dowload VC_redist.x86.exe
- Install MySQL 5.5.62
- Install OsTicket v1.15.8
- Install HeidiSQL

<h2>Installation Steps</h2>

<p>
<img width="1105" alt="Screenshot 2023-11-29 at 10 48 54 PM" src="https://github.com/reginacuenta/osticket-prereqs/assets/150301999/293bf6d6-48cf-42ed-9373-cf628aa04835">

</p>
<p>Create a resource group in Azure.
</p>
<br />

<p>
<img width="1091" alt="Screenshot 2023-11-29 at 10 50 04 PM" src="https://github.com/reginacuenta/osticket-prereqs/assets/150301999/15aed55c-b2ef-4546-8b05-5382cac53ffc">

</p>
<p>
Create a virtual machine.
</p>
<br />

<p>
<img width="1066" alt="Screenshot 2023-11-29 at 10 50 44 PM" src="https://github.com/reginacuenta/osticket-prereqs/assets/150301999/604d1526-760e-4bab-ae49-4e72bc06bd8b">

</p>
<p>
Enable IIS in windows with CGI, Common HTTP Features and IIS Management Console.</p>
<br />

<p>
<img width="819" alt="Screenshot 2023-11-29 at 11 32 40 PM" src="https://github.com/reginacuenta/osticket-prereqs/assets/150301999/0eefe9da-feaf-4f48-890c-ed1619d5d40f">

</p>
<p>
Install PHP Manager for IIS
  <br />

  <p>
<img width="988" alt="Screenshot 2023-11-29 at 11 33 12 PM" src="https://github.com/reginacuenta/osticket-prereqs/assets/150301999/2ff872a6-550f-4a0e-b99b-2c216679531e">

</p>
<p>
Install Rewrite Module
  <br />

   <p>
<img width="787" alt="Screenshot 2023-11-29 at 11 34 15 PM" src="https://github.com/reginacuenta/osticket-prereqs/assets/150301999/a7e3589e-0d64-4619-873f-9eaaf23f226f">

</p>
<p>
Install PHP 7.3.8
  <br />

   <p>
<img width="919" alt="Screenshot 2023-11-29 at 11 37 59 PM" src="https://github.com/reginacuenta/osticket-prereqs/assets/150301999/6dc99aab-d777-45b5-baf9-54baa7317d5c">


</p>
<p>
Install VC_redist.x86.exe.
  <br />

   <p>
<img width="843" alt="Screenshot 2023-11-29 at 11 39 04 PM" src="https://github.com/reginacuenta/osticket-prereqs/assets/150301999/4eca5644-fe91-4fea-85f9-b5a716a40bf5">

</p>
<p>
Install MySQL 5.5.62.
  <br />

   <p>
<img width="1104" alt="Screenshot 2023-11-29 at 11 40 23 PM" src="https://github.com/reginacuenta/osticket-prereqs/assets/150301999/208b840e-c165-4cdd-a332-40607412afc3">


</p>
<p>
Register PHP from within IIS. Install osTicket v1.15.8.
  <br />
