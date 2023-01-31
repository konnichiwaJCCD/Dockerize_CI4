
# Dockerize CodeIgniter 4

Dockerizing CodeIgniter 4 using nginx, MySQL and php-fpm with phpmyadmin is a great way to quickly deploy a fully functional CodeIgniter application. This combination of services allows you to quickly set up a web server with a database and have the CodeIgniter application running in no time. Additionally, you can use phpmyadmin to easily manage the databases, allowing for quick and easy database management. This stack is a great way to quickly deploy a CodeIgniter application and will save time and effort without having to manually set up a web server and database.




## Deployment

You need to include the files inside your CI4 directory

clone or download the files
```bash
git clone https://github.com/konnichiwaJCCD/Dockerize_CI4.git
```
or using ssh
```bash
git clone git@github.com:konnichiwaJCCD/Dockerize_CI4.git
```
Before executing the next commands make sure docker is running in your system

#### Build or setup the docker container
```bash
docker-compose up -d
```
#### Stop the docker container
or you can stop the container from docker app GUI
```bash
docker-compose down
```


## Test Your app

Access your app on your favorite browser

```bash
  localhost:80
```
    
## Contributing

Contributions are always welcome!.

