# Timothy Ng'eno
# Slack: @timngeno

## Static Website Deployment on AWS (Nginx + EC2)

This project demonstrates deployment of a static website on AWS using Nginx as the webserver. The purpose is to provision a site on a publicly accessible EC2 instance, using its public IP Address.

## Deployment description
After provisioning an EC2 instance, Nginx was installed and configured to host the static website files. The server listens on port 80 and serves from the `/var/www/html` directory.

The website file (index.html) was transferred securely to the EC2 instance using `scp`, and appropriate file ownership and permissions were applied to ensure the webserver could read and serve the file correctly.
