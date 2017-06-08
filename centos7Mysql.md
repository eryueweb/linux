centos7 mysql安装
---
1. `sh /usr/local/mysql/scripts/mysql_install_db.sh --user=mysql --basedir=/usr/local/mysql --datadir=/usr/local/mysql/data `

2. `cd bin`

3. `sh /usr/local/mysql/scripts/mysql_install_db.sh --user=mysql --basedir=/usr/local/mysql --datadir=/usr/local/mysql/data  &`

4. `cd ..`

5. `cd mysql/`

6. `./scripts/mysql_install_db.sh --user=mysql --basedir=/usr/local/mysql --datadir=/usr/local/mysql/data`

7. `sh ./scripts/mysql_install_db.sh --user=mysql --basedir=/usr/local/mysql --datadir=/usr/local/mysql/data`

8. `cd scripts/`

9. `more mysql_install_db.sh `

10. `cd /home/`

11. `cd ..`

12. `cd /usr/local/mysql/`

13. `find ./ my_prin`

14. `sh ./scripts/mysql_install_db.sh `

15. `sh ./scripts/mysql_install_db.sh  --user=mysql --basedir=/usr/local/mysql --datadir=/usr/local/mysql/data`

16. `cd extra/`

17. `service mysql start`

18. `chown -R mysql:mysql /var/lib/mysql/`

19. `rpm -qa | grep mysql`

20. `service mysql start`

21. `rpm -e mysql-community-libs-5.6.36-2.el7.x86_64 mysql-community-common-5.6.36-2.el7.x86_64 mysql-community-client-5.6.36-2.el7.x86_64 mysql-community-release-el7-5.noarch mysql-community-server-5.6.36-2.el7.x86_64`

22. `rpm -qa | grep mysql`

23. `cd ..`

24. `cmake -DCMAKE_INSTALL_PREFIX=/usr/local/mysql -DMYSQL_DATADIR=/usr/local/mysql/data -DSYSCONFDIR=/etc -DWITH_MYISAM_STORAGE_ENGINE=1 -DWITH_INNOBASE_STORAGE_ENGINE=1 -DWITH_MEMORY_STORAGE_ENGINE=1 -DWITH_READLINE=1 -DMYSQL_UNIX_ADDR=/var/lib/mysql/mysql.sock -DMYSQL_TCP_PORT=3306 -DENABLED_LOCAL_INFILE=1 -DWITH_PARTITION_STORAGE_ENGINE=1 -DEXTRA_CHARSETS=all -DDEFAULT_CHARSET=utf8 -DDEFAULT_COLLATION=utf8_general_ci`

25. `cmake -DCMAKE_INSTALL_PREFIX=/usr/local/mysql -DMYSQL_DATADIR=/usr/local/mysql/data -DSYSCONFDIR=/etc -DWITH_MYISAM_STORAGE_ENGINE=1 -DWITH_INNOBASE_STORAGE_ENGINE=1 -DWITH_MEMORY_STORAGE_ENGINE=1 -DWITH_READLINE=1 -DMYSQL_UNIX_ADDR=/var/lib/mysql/mysql.sock -DMYSQL_TCP_PORT=3306 -DENABLED_LOCAL_INFILE=1 -DWITH_PARTITION_STORAGE_ENGINE=1 -DEXTRA_CHARSETS=all -DDEFAULT_CHARSET=utf8 -DDEFAULT_COLLATION=utf8_general_ci`

26. `make && make install`

27. `make`

28. `cmake`

29. `sh cmake`

30. `cd cmake`

31. ` yum -y install make gcc-c++ cmake bison-devel  ncurses-devel`

32. ` cd ..`

33. `cmake -DCMAKE_INSTALL_PREFIX=/usr/local/mysql -DMYSQL_DATADIR=/usr/local/mysql/data -DSYSCONFDIR=/etc -DWITH_MYISAM_STORAGE_ENGINE=1 -DWITH_INNOBASE_STORAGE_ENGINE=1 -DWITH_MEMORY_STORAGE_ENGINE=1 -DWITH_READLINE=1 -DMYSQL_UNIX_ADDR=/var/lib/mysql/mysql.sock -DMYSQL_TCP_PORT=3306 -DENABLED_LOCAL_INFILE=1 -DWITH_PARTITION_STORAGE_ENGINE=1 -DEXTRA_CHARSETS=all -DDEFAULT_CHARSET=utf8 -DDEFAULT_COLLATION=utf8_general_ci`

34. `make && make install`

35. `cd scripts/`

36. `sh mysql_install_db.sh --basedir=/usr/local/mysql --datadir=/usr/local/mysql/data --user=mysql`

37. `cd ..`

38. `cp support-files/mysql.server /etc/init.d/mysql`

39. `chkconfig mysql on`

40. `more /etc/profile`

41. `vi /etc/profile`

42. `source /etc/profile`

43. `mysql`

44. `su - mysql`

45. `service mysql start`

46. `chmod +x  /etc/init.d/mysql`

47. `service mysql start`

48. `mysql -uroot`

49. `ps -ef |grep mysql`

50. `netstat -ntlp |grep 26214`

51. `su - mysql`

52. `mysql`

53. `mysql root'@'localhost`

54. `mysql -uroot`

55. `mysql -uroot -p`

56. 查看服务器内存占用情况  
`free -m`   

57. `mysql`
