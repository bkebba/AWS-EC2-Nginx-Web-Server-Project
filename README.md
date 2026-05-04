# AWS EC2 Nginx Web Server Project

## Description
I created a Linux EC2 instance on AWS.
I installed Nginx and deployed a simple web page.

## What I did
- Launched an EC2 instance
- Connected using SSH
- Installed Nginx
- Started and enabled Nginx
- Opened port 80
- Deployed a custom webpage

## What I learned
- How to launch an EC2 instance
- How to connect using SSH
- How to install and manage Nginx
- How to open HTTP traffic using security groups
- How to deploy a custom webpage on AWS

## Screenshots

The screenshots in this repository show:

- EC2 security group configuration
- EC2 instance details
- SSH connection steps
- Successful SSH connection
- Linux OS information
- Network and hostname checks
- Nginx installation
- Nginx service started and enabled
- Local test using curl localhost
- Port 80 open for HTTP traffic
- Nginx welcome page
- Custom webpage deployed

## Commands used
```bash
sudo yum update -y
sudo yum install nginx -y
sudo systemctl start nginx
sudo systemctl enable nginx
sudo systemctl status nginx
curl localhost
sudo nano /usr/share/nginx/html/index.html
sudo systemctl restart nginx
cat /etc/os-release
ifconfig
hostname


