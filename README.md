this file contains,service_1,service_2,nginx and docker-compose.yml

service_1 contains of main.go and dockerfile,this dockerfile helps to build the goland application image which consists of server page with ping page and hello page with port number 8001

service_2 consists of app.py and dockerfile which helps us to create image of python application with server pages ping and hello with port number 8002

nginx folser consists of configure file where service1 and service2 are configured and a dockerfile init to make a image with these to services configured

docker-compose.yml by building it we can build nginx server with service1 and service2 configurations


steps
1.clone the repository
2.install docker and docker-compose
3.build command docker-compose up --build -d
4.image and container are build
5.check the servers page with <instance.ip>:8080/service1/ping
<instance.ip>:8080/service1/hello
<instance.ip>:8080/service2/ping
<instance.ip>:8080/service1/hello
