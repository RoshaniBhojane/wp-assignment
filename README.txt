1. Download and unzip roshani_wordpress folder in your development folder (Ex. c:\xampp\htdocs\)

2. Create roshani_wordpress database and import roshani_wordpress.sql file.

3. Open wp-config.php file (Ex. c:\xampp\htdocs\roshani_wordpress\wp-config.php) and change database username & password with your. If host is different then change host name also.

4. Open browser and run application (Ex. http://localhost/roshani_wordpress/) 

5. if your host URI is changed then go to database, open 'wp_options' table, search 'option_name'='siteurl' & 'option_name'='home' and changes thier 'option_value' with your new url.

6.  Open browser and open admin panel (Ex. http://localhost/roshani_wordpress/wp-admin) 
Username: admin
Password: admin

7. For change upload path from wp-content/upload to /files add "define('UPLOADS',''.'files')" in wp-config.php file.

8. Allied custome wordpress theme created.