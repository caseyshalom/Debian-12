# Change Directory
```sh
cd /var/www/html
   ```
# Install Unzip
```sh
apt install unzip -y
   ```
# wget
```sh
wget https://wordpress.org/latest.zip
   ```
# unzip
```sh
unzip latest.zip
   ```
# Permission
```sh
chmod 777 /var/www/html/wordpress
   ```
# Database Wordpress
```sh
mysql -u root -p
      password : 123

create database wordpress;
create user 'casey'@'localhost' identified by '123';
grant all privileges on *.* to 'casey'@'localhost';
flush privileges;
quit; 
   ```
# Setting Database Wordpress
```sh
cd /var/www/html/wordpress
cp wp-config-sample.php wp-config.php
nano wp-config.php
   ```
# Restart Apache2
```sh
systemctl restart apache2
   ```

# Go page
# Install Wordpress
```sh
Site Name : casey
Username : casey
Password : 123
email : casey@gmail.com
   ```
