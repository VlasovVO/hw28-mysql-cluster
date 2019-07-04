# hw28-mysql-cluster

Запуск: **vagrant up**

Порт наружу: 6446

Проверить работоспособность можно скриптами *mysql.sh*:

```bash
[vagrant@elk ~]$ ./mysql.sh --execute="SHOW DATABASES" | head
mysql: [Warning] Using a password on the command line interface can be insecure.
+-------------------------------+
| Database                      |
+-------------------------------+
| information_schema            |
| mysql                         |
| mysql_innodb_cluster_metadata |
| performance_schema            |
| sys                           |
+-------------------------------+
```