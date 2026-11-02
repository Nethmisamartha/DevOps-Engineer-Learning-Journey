# Nginx Web Server Deployment Practical

This section documents my hands-on experience installing, configuring, and testing an Nginx web server using Ubuntu Linux on Killercoda.

## Topics Covered

- Installing Nginx
- Starting and stopping Nginx
- Enabling Nginx service
- Creating a custom HTML web page
- Deploying a website
- Testing the web server using curl
- Checking HTTP response status

## Commands Practiced

```bash
sudo apt update
sudo apt install nginx -y
sudo systemctl start nginx
sudo systemctl enable nginx
sudo systemctl status nginx
```

## Website Deployment

Created a custom HTML page:

```bash
echo '<h1>My First DevOps Website</h1><p>Successfully Deployed on Ubuntu Linux!</p>' | sudo tee /var/www/html/index.html
```

Tested the website:

```bash
curl http://localhost
curl -I http://localhost
```

## Practical Results

- Installed and started the Nginx web server.
- Created and deployed a custom HTML page.
- Successfully accessed the website using localhost.
- Received an HTTP 200 OK response.

## Practical Environment

- Platform: Killercoda
- Operating System: Ubuntu Linux
- Web Server: Nginx

## Learning Outcome

Gained practical experience deploying and testing a basic website using an Nginx web server.
