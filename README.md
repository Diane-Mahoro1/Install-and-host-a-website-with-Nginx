# Objective 
Install and configure Nginx on ubuntu(WSL)

# steps taken
1. sudo apt update
2. sudo apt install nginx
3. sudo service nginx start

# Issue encounted 
Can't access index.html 

# solution 
used the commend chmodd 644(below) to provide permission access to index.html 
sudo chmod 644 /var/www/html/index.html

# lesson leanrt 
File permissions affect user access to the file 
