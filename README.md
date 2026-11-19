Apache HTTP Web Server Configuration on Linux

Project Overview

This project demonstrates the installation, configuration, and deployment of an Apache HTTP Web Server on an Ubuntu Linux environment.

A custom HTML webpage is hosted using Apache to verify that the web server is installed and functioning correctly.

Objective

To provision and configure an Apache HTTP Web Server (httpd) on a Linux server and host a custom webpage accessible through a web browser.

Technology Stack

* Operating System: Ubuntu 24.04.5 LTS
* Web Server: Apache HTTP Server 2.4
* Web Technologies: HTML
* Environment: GitHub Codespaces
* Version Control: Git and GitHub

Implementation Steps

1. Update Package Repository

sudo apt update

2. Install Apache Web Server

sudo apt install apache2 -y

3. Verify Apache Installation

apache2 -v

4. Start Apache Service

sudo service apache2 start

5. Verify Apache Service Status

sudo service apache2 status

6. Create a Custom HTML Webpage

The webpage is hosted at:

/var/www/html/index.html

7. Verify Web Server Response

curl http://localhost

Check the HTTP response:

curl -I http://localhost

Expected response:

HTTP/1.1 200 OK

Custom Webpage

The hosted webpage displays:

* Welcome to My Website!
* Linux Fundamentals Assignment
* Apache HTTP Server configuration status
* Ubuntu operating system information
* Apache web server version

Project Structure

demo-vm/
│
├── README.md
├── index.html

Verification Results

* Apache HTTP Server installed successfully.
* Apache service started successfully.
* Custom HTML webpage created and hosted.
* Port 80 forwarded in GitHub Codespaces.
* Webpage accessed successfully through Google Chrome.
* HTTP response verified with status code 200 OK.

Conclusion

Successfully installed and configured Apache HTTP Server on Ubuntu Linux and hosted a custom HTML webpage.

The successful browser access and HTTP 200 OK response confirm that the Apache web server is functioning correctly.

⸻

Project: Linux Fundamentals Assignment
Repository: demo-vm
Author: Chitra Gautam
