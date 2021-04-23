# kio-sog-inception

The list of available updates is more than a week old.
To check for new updates run: sudo apt update

********************************************************************************

Welcome to One-Click OpenLiteSpeed WordPress Server.
To keep this server secure, the firewall is enabled.
All ports are BLOCKED except 22 (SSH), 80 (HTTP) and 443 (HTTPS).

WordPress One-Click Quickstart guide:
* https://docs.litespeedtech.com/cloud/images/wordpress/

In a web browser, you can view:   
* The new WordPress site: http://3.23.104.49
* The phpMyAdmin: http://3.23.104.49/phpmyadmin

On the server:
* The default web root is located at /var/www/html
* You can get the MySQL root password and MySQL WordPress user password with command:
   sudo cat /home/ubuntu/.db_password
* You can get the Web Admin admin password with the following command:
   sudo cat /home/ubuntu/.litespeed_password
* The WordPress Cache plugin, LSCache, is located at
   /var/www/html/wp-content/plugins/litespeed-cache
* The phpMyAdmin is located at /var/www/phpmyadmin
* A script will run that will allow you to add a domain to the web server and implement SSL.

System Status:
  Load : 0.00, 0.02, 0.06
  CPU  : 3.47354%
  RAM  : 257/978MB (26.28%)
  Disk : 2/7GB (34%)

********************************************************************************

To visit your apps by domain instead of IP, please enter a valid domain.
If you don't have one yet, you may cancel this process by pressing CTRL+C and continuing to SSH.
This prompt will open again the next time you log in, and will continue to do so until you finish the setup.
Make sure the domain's DNS record has been properly pointed to this server.
Enter the root domain only, then the system will add both the root domain and the www domain for you.