# auto_install_ci
auto installer for codeigniter.
this is simple utility for codeigniter which is Run on Client machine and modify some configuration files according to
the need of Client Envoirnment .when auto_install_ci runs it automatically changes the following files.
#Files auto_install_ci changes
1. application/Config.php(for encryption key and base Url);
2. application/route.php (for default controller);
2. application/database.php (for database setting);
and if you are using Ion_auth it also overwrite it'content as well.
