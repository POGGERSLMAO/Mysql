# Mysql
Intro till MYSQL

## Starta server

Kör igång Ubuntu

kör

  sudo apt update
  sudo apt upgrade

  sudo service mysql restart
  sudo service apache2 restart
  
Om apache2 strular på grund av port 80, så stoppa BRANCHCACHE i "Tjänster" 


## MYSQL 

**setup**
Kör 

	sudo mysql -u root

grant all prvileges on *.* to 'username'@'localhost' identified by 'password';
