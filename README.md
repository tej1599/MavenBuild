HelloWorld Servlet example with corresponding Dockerfile

Use Maven Build first to create war file in Target folder.

mvn clean package

Artifact will be created in target folder.

docker build -t mavenbuild .

Once this is done u will be see image using docker images

Use below command to run the container

docker run -d -p 8080:8080 --name mavenbuild mavenbuild

This is my new commit for jenkins build no #
This is another commit for the new build no 7

#include studio.h
#include math.h
Webook commit made on 22nd March - Jantacurfewday 
Stay home Stay Healthy
