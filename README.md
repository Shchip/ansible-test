This role installs and configures the nginx + php5-fpm + mysql + phpmyadmin and Sout Realtim.

Options for installation and configuration of applications are in /group_vars/all

After install we can see test php page (http://hostname.test.php), working phpmyadmin (http://hostname.phpmyadmin) and realtime monitoring of target server resources (http://hostname:port_in_var)



Before user template configuration, all config files are made backup copies, if there is on the target server.
