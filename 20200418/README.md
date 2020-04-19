
//import or export images
docker save -o images.tar image1
export, load, import

docker image build -t zhanish/imagename:tag ./directory
docker image push zhanish/imagename:tag 
docker container run -d --name web -P 8080:8080 zhanish/imagename 

docker image ls -- to check all the image running

=============================================
Docker Compose
docker-compose up --build


--Create Project
--Create Dockerfile and define container 
--Create docker-compose.yml with the information to run the file
docker-compose up/down 
docker-compose up -d -- detached mode..
--switch to another terminal and run 
docker image ls
--your image should be displayed
docker inspect tag/id
===
Allow code to change on fly
Volumes: 
 -.:/code













