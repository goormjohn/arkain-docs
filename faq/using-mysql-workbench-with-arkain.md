---
icon: circle-5
---

# Using MySQL Workbench with Arkain

### **Configure mysqld.cnf** <a href="#configure-mysqldcnf" id="configure-mysqldcnf"></a>

Edit /etc/mysql/mysql.conf.d/mysqld.cnf using vi.

```
#bind-address = 127.0.0.1 <- make it comment
```

Please enter the command below to restart mysql.

```bash
service mysql restart
```

### **Grant permission to MySQL account** <a href="#grant-permission-to-mysql-account" id="grant-permission-to-mysql-account"></a>

Please grant permission using the command below.

```bash
$ mysql -u root -p
Enter password:
Welcome to the MySQL monitor.  Commands end with ; or \\g.
Your MySQL connection id is 4
Server version: 5.7.29-0ubuntu0.18.04.1 (Ubuntu)

Copyright (c) 2000, 2020, Oracle and/or its affiliates. All rights reserved.

Oracle is a registered trademark of Oracle Corporation and/or its
affiliates. Other names may be trademarks of their respective
owners.

Type 'help;' or '\\h' for help. Type '\\c' to clear the current input statement.

mysql> GRANT ALL ON *.* TO root@'%' IDENTIFIED BY 'pass';
Query OK, 0 rows affected, 1 warning (0.00 sec)

mysql> FLUSH PRIVILEGES;
Query OK, 0 rows affected (0.00 sec)
```

### **MySQL Port Forwarding Configuration** <a href="#mysql-port-forwarding-configuration" id="mysql-port-forwarding-configuration"></a>

1. From the top menu, click **\[Container] → \[Port Forwarding Settings]**
2. Select **\[MySQL]** as the type and click the **\[Register]** button.

![image alt text](https://mkdocs-mxedr.run.goorm.site/assets/images/Using-MySQL-Workbench-with-Arkain.en_63.png)

### **Connect to the MySQL server in the Arkain container using mysqlsh** <a href="#connect-to-the-mysql-server-in-the-arkain-container-using-mysqlsh" id="connect-to-the-mysql-server-in-the-arkain-container-using-mysqlsh"></a>

Please connect using the command below.

```bash
$ mysqlsh root@54.184.110.197:59700
Please provide the password for 'root@54.184.110.197:59700': 
Save password for 'root@54.184.110.197:59700'? [Y]es/[N]o/Ne[v]er (default No): 
MySQL Shell 8.0.19

Copyright (c) 2016, 2019, Oracle and/or its affiliates. All rights reserved.
Oracle is a registered trademark of Oracle Corporation and/or its affiliates.
Other names may be trademarks of their respective owners.

Type '\\help' or '\\?' for help; '\\quit' to exit.
Creating a session to 'root@54.184.110.197:59700'
Fetching schema names for autocompletion... Press ^C to stop.
Your MySQL connection id is 6
Server version: 5.7.29-0ubuntu0.18.04.1 (Ubuntu)
No default schema selected; type \\use <schema> to set one.
MySQL  54.184.110.197:59700 ssl  JS >
```

