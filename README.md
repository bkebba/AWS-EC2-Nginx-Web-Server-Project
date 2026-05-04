# AWS-EC2-Nginx-Web-Server-Project
I created a Linux EC2 instance on AWS and installed Nginx and deployed a simple web page.

## What I did
- Launched EC2 instance
- Connected using SSH
- Installed Nginx
- Started and enabled Nginx
- Opened port 80
- Deployed a custom webpage

## Commands used
**# Update system
sudo yum update -y

# Install Nginx
sudo yum install nginx -y

# Start Nginx
sudo systemctl start nginx

# Enable Nginx on boot
sudo systemctl enable nginx

# Check Nginx status
sudo systemctl status nginx

# Test web server locally
curl localhost

# Edit default webpage
sudo nano /usr/share/nginx/html/index.html

# Restart Nginx
sudo systemctl restart nginx

# Check OS version
cat /etc/os-release

# Check network info
ifconfig
