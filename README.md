## Screenshots

![App Screenshot](https://i.hizliresim.com/jqunbz5.jpg)


## Mysql Create Database Sql String

```sql
DROP TABLE IF EXISTS `employee`;
CREATE TABLE `employee` (
  `id` int(6) unsigned NOT NULL AUTO_INCREMENT,
  `name` varchar(30) NOT NULL,
  `city` varchar(30) NOT NULL,
  PRIMARY KEY (`id`)
) ENGINE=InnoDB AUTO_INCREMENT=1 DEFAULT CHARSET=latin1;
```


## Tech Stack

**Client:** Bootstrap, tmpl

**Server:** Go, Mysql

## Referance

https://www.golangprograms.com/example-of-golang-crud-using-mysql-from-scratch.html
