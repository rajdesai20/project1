Cloud project 1 based on Docker

This project includes creating an image using docker and also creating a repository on docker and then pushing the image on docker.

Steps of Project1:
1. Creating an instance based in ubuntu.
2. Allow acces to port 4000 through any IP and port 80 thorugh HTTP protocol..
3. Command : $docker build
4.$docker run -p 4000:80
5.$docker tag image rajdesai20/project1:myflask
6.$docker push rajdesai20/project1:myflask
7.$docker pull rajdesai20/python:flask docker run -p 8081:80 rajdesai20/project1:flask

Note: These commands can be found on the official Docker documentation for creating,pushing and pulling image.