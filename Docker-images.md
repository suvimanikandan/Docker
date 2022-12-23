What is the docker images?     
->docker images are just a template of a docker containers and it is very simple to snapshot image with smaller in size.
single docker image can be used to create a multiple containers for different environment like development,UAT and production.

->docker images are very light weighted ,small and fast to deploy the containers.

->docker images are consits of many layeers with unique image id from base images.each layers may have some changes commited on top of a exisiting layers.

->Docker images are read only layer of the docker containers and docker containers are read write layers of docker images


container layer ->read &write ->Read&write     
layer 1 run yum install -ywget->Read only   
base layer  ->read only       



docker images search ubuntu   

docker pull ubuntu

docker run -d -it --name myhttpd-qa -p 81:80  httpd       
docker inspect->networking check the ip address ,ports



