# FRONTEND :

The frontend is the service in Todo to serve the web content over Nginx.

To Update and Install Nginx run below commands.

```
  # apt update

  # apt install nginx 

  # systemctl enable nginx 

  # systemctl start nginx 
```
This service is written in NodeJS, Hence need to install NodeJS in the system.
```
# apt update

# apt install npm -y

```
Deploy in Nginx Default Location.
```
# cd /var/www/html/

# mkdir todoapp

# cd todoapp/
```

Lets clone the code from github repository

```
# git clone https://github.com/zelar-soft-todoapp/frontend.git

# cd frontend/

# npm install

# npm run build

```
Finally restart the service once to effect the changes by the below cammand.

```
# systemctl restart nginx

# npm start
```
