# E_Commerce 
##How you work
First you have to extract E-Commerce-Website-master.zip file and put this folder to your server.Then enter this folder and import source.sql database file to your mysql database.After you open connection.php file and change your user name(root) and password(tkmysql).Now go to your browser and go to this link http://localhost/E-Commerce-Website-master/index.php . This is my link, which is my local server.You paste your own.

##For second project
You extract ecommerce_batch17.zip file and and put this folder to your local server.Then enter this folder and import ecommerce_batch17.sql database file to your phpmyadmin server database.Go to /application/config/database.php and change these files as your own, 
$db['default']['hostname'] = 'localhost';
$db['default']['username'] = 'root';
$db['default']['password'] = 'your server password';
$db['default']['database'] = 'your database name';
$db['default']['dbdriver'] = 'mysql';
