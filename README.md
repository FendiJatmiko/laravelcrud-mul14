# laravelcrud-mul14
laravel container based on debian:stretch and php 7.1 
based on laravel crud demo from https://github.com/mul14/laravel-crud-demo

## How to use this images 
* just build with standard build process, i.e : 
````````
docker build -t laravelcrud .
```````` 
* launch images 
``````````
docker run -d -p 8000:8000 --rm laravelcrud 
``````````
* and you can access it at :
``````````
localhost:8000
``````````
* or you could just pull from dockerhub
``````````
docker pull pndxdcode/laravelcrud-mul14
``````````
