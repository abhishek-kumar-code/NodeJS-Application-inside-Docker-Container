# NodeJS-Application-inside-Docker-Container
Making real world projects with Docker by hosting a NodeJS application

# Building our docker container
docker build -t akumar/web_applicaion .

# Running our docker container
docker run -p 8080:8080 akumar/web_application

The site is hosted on localhost. For windows, do a docker-machine ls. The default running machine indicates the URL for the launched application. For this application, the URL is http://192.168.99.100:<port#>
