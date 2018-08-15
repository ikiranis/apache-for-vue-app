## Create Docker with Apache/PHP Vue App

* Edit **.env** file with your settings

* Run 
```
docker-compose up -d
```

* **/www** folder will be created

* Put your Vue application files in **/www** folder

* Edit Vue .env files, install depedencies etc

You can create your apache image instead of **apps4net/vue-apache** with the command:

```
docker build -t vue-apache docker/apache
```

Then use this at **docker-compose.yml** file

``` 
image: vue-apache
```