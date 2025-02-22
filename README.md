# Web Server

## How to Install
1. Configure the repository
 ```sh
   nano /etc/apt/sources.list
   ```
2. Update Packages
 ```sh
   sudo apt update
   ```
3. Install Apache2
 ```sh
   sudo apt install apache2 -y
   ```
4. Start, enable, and status
 ```sh
   sudo systemctl start apache2
   sudo systemctl enable apache2
   sudo systemctl status apache2
   ```
5. Change DocumentRoot
 ```sh
   cd /etc/apache2/sites-available
   nano 000-default.conf
   ```
6. Change Port (Optional)
 ```sh
   nano /etc/apache2/ports.conf
   ```
