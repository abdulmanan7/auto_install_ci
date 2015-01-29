# Auto install CodeIgniter
Configure the CI database settings programmatically.   
it's OSCommerce, Joomla, Wordpress etc,like installation utility.  
That Provide the user to submit a form with database information like admin user atc.  
This is simple utility for codeigniter which is Run on Client machine and modify some configuration files according to
the need of Client.  
#How to run / Use
There are three steps to run the utility.  
1.Place the auto_install_ci at application level (not in the application folder),rename it to install;  
2.Add your db in the /database.xml file;  
3.Now to run just type your base url /install;  
Files auto_install_ci changes when run.  
i. application/Config.php(for encryption key and base Url);  
ii. application/route.php (for default controller);  
iii. application/database.php (for database setting);  

and if you are using Ion_auth it will also be overwrite it'content as well.  

|
|
for more help contact me at my twetter account @abdulmanan7.
