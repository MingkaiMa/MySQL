# MySQL
Database


Note:
1) start sever: command line: /usr/local/mysql/bin/mysql -u root -p




Problems:

1)Command:  LOAD DATA LOCAL INFILE '/Users/marktoms/Desktop/menagerie-db/pet.txt' INTO TABLE pet;
  Problem: ERROR 1148 (42000): The used command is not allowed with this MySQL version.
  workaround: /usr/local/mysql/bin/mysql --local-infile=1 -u root -p
