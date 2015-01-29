# auto_install_ci
auto installer for codeigniter.
this is simple utility for codeigniter which is Run on Client machine and modify some configuration files according to
the need of Client.when auto_install_ci runs it automatically changes the following files.
#Files auto_install_ci changes
1. application/Config.php(for encryption key and base Url);
2. application/route.php (for default controller);
2. application/database.php (for database setting);
and if you are using Ion_auth it also overwrite it'content as well.
#How to Run 
there are three steps to run the utility.
1.place the auto_install_ci at application level (not in the application folder),rename it to install.
2.add your db in the /database.xml file.
3.now to run just type your base url /install.
|
|
for more help contact me at @abdulmanan7.
