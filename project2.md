# PROJECT 2: LEMP STACK IMPLEMENTATION
## Step 1 – Installing the Nginx Web Server
### Install nginx
- `sudo apt update`
- `sudo apt install nginx`
- `sudo systemctl status nginx`
![NginX installation](/images/nginx-install.jpg)
![NginX status](/images/nginx-status.jpg)
### Confirm that Nginx server can respond to requests from the Internet.
[My NginX Server](http://44.204.228.6/)
![NginX server](/images/nginx-server.jpg)

## STEP 2 — Installing mysql
### Install mysql
- `$ sudo apt install mysql-server`
![mysql install](/images/mysql-install.jpg)
### Log into mysql
- `$ sudo mysql`
![mysql login](/images/mysql-login.jpg)
### Set mysql root user password
- `ALTER USER 'root'@'localhost' IDENTIFIED WITH mysql_native_password BY 'PassWord.1';`
- `mysql> exit`
![mysql root user password](/images/rootuser-password.jpg)
### Log into mysql again after setting root user password
- `sudo mysql -p`
![mysql login](/images/rootuser-password.jpg)