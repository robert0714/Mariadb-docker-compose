# Mariadb
```bash
root@cs-983647568396-default:/# mysql -uroot -pthisismyrootpassword
Welcome to the MariaDB monitor.  Commands end with ; or \g.
Your MariaDB connection id is 5
Server version: 10.11.5-MariaDB-1:10.11.5+maria~ubu2204 mariadb.org binary distribution

Copyright (c) 2000, 2018, Oracle, MariaDB Corporation Ab and others.

Type 'help;' or '\h' for help. Type '\c' to clear the current input statement.

MariaDB [(none)]> show databases;
+--------------------+
| Database           |
+--------------------+
| databasename       |
| information_schema |
| mysql              |
| performance_schema |
| sys                |
+--------------------+
5 rows in set (0.001 sec)

MariaDB [(none)]> 
```

# API
* ``curl localhost:8080/PushMessagesProj/checkVersion``
* ``curl localhost:8080/PushMessagesProj/checkPropertiesVersion``
* anthos: ``https://8080-cs-983647568396-default.cs-asia-east1-vger.cloudshell.dev/PushMessagesProj/checkPropertiesVersion?authuser=0&redirectedPreviously=true``




