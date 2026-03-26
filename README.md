# Linux EC2 Monitoring Project

## Overview
This project demonstrates deploying a Linux web server on AWS EC2 with Nginx and system monitoring using Node Exporter. It showcases real-world Linux administration and DevOps skills.

## Features
- Ubuntu EC2 instance setup (Free Tier)
- Nginx web server deployed with a static website
- Node Exporter installed for real-time system monitoring (CPU, RAM, Disk)
- AWS Security Groups configured for proper access
- Systemd service setup for Node Exporter
- Metrics accessible via browser at port 9100

## Live Project Links
- Website: [http://13.60.219.150](http://13.60.219.150)  
- Node Exporter Metrics: [http://13.60.219.150:9100](http://13.60.219.150:9100)

## Screenshots
![Website Screenshot](https://via.placeholder.com/600x400.png?text=Website+Screenshot)  
![Node Exporter Metrics](https://via.placeholder.com/600x400.png?text=Node+Exporter+Metrics)

## Skills Demonstrated
- Linux server administration
- AWS EC2 deployment
- Nginx web server management
- Monitoring using Prometheus Node Exporter
- Systemd service management
- Networking: opening ports with Security Groups

## Installation Steps
1. Launch an Ubuntu EC2 instance
2. SSH into the instance
3. Install Nginx:
   ```bash
   sudo apt update
   sudo apt install nginx -y
   sudo systemctl start nginx
   sudo systemctl enable nginx
