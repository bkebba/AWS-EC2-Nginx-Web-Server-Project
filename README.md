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

## Commands used


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

What I learned
How to launch an EC2 instance
How to connect using SSH
How to install and manage Nginx
How to open HTTP traffic using security groups
How to deploy a custom webpage on AWS
