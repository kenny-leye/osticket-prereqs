🔹 osTicket – Prerequisites and Installation

This tutorial outlines the prerequisites and step-by-step installation of the open-source help desk ticketing system osTicket in a cloud-based environment using Microsoft Azure.

🎥 Video Demonstration

YouTube: How to Install osTicket with Prerequisites
(Optional – you can add a link if you used one)

🧰 Environments and Technologies Used
Microsoft Azure (Virtual Machines / Compute)
Remote Desktop Protocol (RDP)
Internet Information Services (IIS)
PHP Manager
MySQL Database
💻 Operating Systems Used
Windows Server 2019
Windows 10 (for remote access)
📋 List of Prerequisites

Before installing osTicket, the following components were required:

A Microsoft Azure account
A configured Virtual Machine (Windows Server)
Remote Desktop access to the VM
IIS (Web Server) installed and running
PHP installed and configured
MySQL installed for database management
osTicket installation files
⚙️ Installation Steps
Step 1: Create Virtual Machine

A Windows Server Virtual Machine was created in Microsoft Azure. Remote Desktop was used to connect to the server for configuration.

Step 2: Install IIS (Web Server)

Using Server Manager, IIS was installed to host the osTicket web application.

Step 3: Install PHP

PHP Manager was installed and configured to allow IIS to process PHP files required by osTicket.

Step 4: Install MySQL

MySQL Server was installed to create and manage the database required for osTicket.

Step 5: Download and Configure osTicket

The osTicket installation files were downloaded and extracted into the IIS web directory. Configuration files were modified to enable setup.

Step 6: Complete Web Installation

Using a web browser, the osTicket setup page was accessed. Database details were entered, and installation was completed successfully.
