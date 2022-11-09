# Python online compiler

## Frontend 

### Installation

For making a frontend container just run these comands in your command line:

1. Find and change your application and Docker file path using command line (Windows/Linux or Mac): 
> `$ cd \path\to\app`
2.  Make sure Docker and source files exists, you can use navigation commands like *cd* or *dir* on the console.
3. Then exectute these commands:
>`$ docker build -t <docker-image-name> .`

>`$ docker run -dit --name <container-name> -p 8080:80 <docker-inage-name>`
4. Finally, visit the [Apache HTTP Server](http://localhost:8080/) and you will see It works!





