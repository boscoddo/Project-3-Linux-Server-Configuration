# Project 3: Linux Server Configuration
## Description
This project was to configure a Linux Web Server to host my web Sports Catalog application that I created in Project 2.  
Software that I that installed for this project includes Linux Ubuntu, python, PostgreSQL, git, Apache, ufw, apt, finger, and libapache2-mod-wsgi-py3

## Linux Configurations
- The Linux server instance that I selected is Amazon Lightsail.
- Linux Instance Choosen: Ubuntu
- Installed and configure Apache to serve a Python mod_wsgi application.  
- Installed and configure PostgreSQL for database setup.
- Installed git
- Create a user account name: grader and gave sudo access.
  - ssh grader@54.68.158.48 -p 2200 -i ~/.ssh/XXXXXXXXXX
- Create a database user name: catalog (pass: catalog) that has limited permissions to my catalog database only.

## IP Addresses
- Linux Server: 54.68.158.48
- SSH (port: 2200)
- HTTP (port 80)
- NTP (port 123)
- Complete URL: http://54.68.158.48.xip.io

## Third Party Resources
- Amazon LightSail
- Linux Ubuntu
- Putty
- GitBash
- Sublime

## How to run
* 1. Open Chrome Browser to http://54.68.158.48.xip.io to view the app.
* 2. Log Into the app to be able to edit/delete items.
* 3. Enjoy!
