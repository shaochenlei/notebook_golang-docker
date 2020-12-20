# notebook_golang-docker
<center>The learning notebook for backend</center>


:horse:Learning from Youtube website

URL: https://www.youtube.com/watch?v=rx6CPDK_5mU&list=PLy_6D98if3ULEtXtNSY_2qN21VCKgo 

1.Use dbdiagram.io Postgres SQL Database

![image-20201216214129122](C:\Users\94653\AppData\Roaming\Typora\typora-user-images\image-20201216214129122.png)

2.List

* Install Docker Desktop 

* Run Postgres container

* design database

<iframe width="560" height="315" src='https://dbdiagram.io/embed/5fdf056b9a6c525a03bbb950'> </iframe>

docker pull postgres:12-alpine

docker run --name postgres12 -p 5432:5432 -e POSTGRES_USER=root -e POSTGRES_PASSWORD=secret -d postgres:12-alpine

* Download TablePlus ,Tips: Ctrl+ R to refresh table