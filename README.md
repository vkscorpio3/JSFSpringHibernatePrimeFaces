JSFSpringHibernatePrimeFaces
============================

This application contains a integration of JSF, Primefaces, Spring and Hibernate. It carries out simple CRUD functionalities.


Table sql:
CREATE TABLE userdb.Employee (
  `id` int(11) unsigned NOT NULL AUTO_INCREMENT,
  `name` varchar(20) DEFAULT NULL,
  `lastname` varchar(20) DEFAULT NULL,
  `reg_date` timestamp DEFAULT 0,
  PRIMARY KEY (`id`)
) ENGINE=InnoDB AUTO_INCREMENT=19 DEFAULT CHARSET=utf8;
