# 🎫 osTicket Help Desk Environment
Hands-on osTicket help desk lab simulating an enterprise IT Support hosted on a Raspberry Pi

## Introduction
In this lab I used a Raspberry Pi to host osTicket to simulate common IT support and ticketing workflows in an enterprise environment. On the Raspberry pi I configured Secure Shell during the imaging process and did all configurations through the command line on a different workstation. osTicket is locally hosted on the Pi using an Apache server with a SQL database to store ticket data.

## The lab includes:

- ✅ Apache web server configuration
- ✅ MySQL/MariaDB database configuration
- ✅ PHP configuration
- ✅ osTicket installation and deployment
- ✅ Help desk users and agents
- ✅ Departments and support teams
- ✅ Ticket priorities and SLAs
- ✅ Help topics and ticket categorization
- ✅ Ticket assignment and escalation
- ✅ Simulated end-user support requests
- ✅ Ticket troubleshooting and resolution
- ✅ Active Directory help desk scenarios

## Architecture
osTicket uses a multi-tier web application architecture. Apache provides a web server that will handle HTTP requests, PHP is used for the application code, and the MariaDB database provides a storage space for users, tickets, departments, and configurations. I don't go over setting up the Apache server, installing PHP, or setting up the databse but the screenshots below show that they are running on the Pi

CLI Command: sudo systemctl apache2

CLI Command: sudo systemctl mariadb

CLI Command: php --version

## 🎫 osTicket Deployment & Help Desk Environment
If you check out my AD-

