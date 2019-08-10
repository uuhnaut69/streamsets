# Replicating Mysql to elastic 

Create schema's name: ***binlog***

Create test table: 

```
CREATE TABLE `job` (
  `id` int(11) NOT NULL AUTO_INCREMENT,
  `job` varchar(45) NOT NULL,
  `salary` int(11) NOT NULL,
  PRIMARY KEY (`id`)
) ENGINE=InnoDB AUTO_INCREMENT=5 DEFAULT CHARSET=latin1;
```

Test insert commands:
```
insert job(job,salary) values ("java dev",1000);

insert job(job,salary) values ("python dev",1000);
```
