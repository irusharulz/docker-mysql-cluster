# DevOps Assignment_3

## Problem Statement
> Create a MySQL cluster using the docker-compose. You need to create a 3 node cluster and that cluster must be accessible from the outside world.

## How to run problem solution

> Before going to execute below, please check whether you have installed docker & docker-compose in your machine.

``` 
git clone https://github.com/irusharulz/docker-mysql-cluster.git 
```

> After that locate to docker-mysql directory by using below command

``` 
cd docker-mysql-cluster/ 
```

> Type below command to create the services & run

``` 
docker-compose up -d
```

> After that all the services has up. You can check status of the services by using below command. If connection runing smoothly need to have 6 services.

``` 
docker ps
```

> Check mysql cluster from outside. Go to MySQL Workbench and create a connection by below configuration. 


``` 
Connection Name: TestConnection1
Hostname: localhost
Port: 3306
Username: irusha
Password: asd@admin   
```

``` 
Connection Name: TestConnection2
Hostname: localhost
Port: 3307
Username: irusha
Password: asd@admin   
```







