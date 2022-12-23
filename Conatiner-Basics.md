What is Containerization(Container)?
-->Containerization is a light weight virtualization technology alternative to hypervisor virtualization.
Any Application can be bundled in a container can run without any woriess about dependencies ,libraries and binaries.
-->Because container creates the isolated environment with all the required dependencies,libraries and binaries to run your application without any issue.
-->hence you can build the packages,ship the application to any environment and run  it.

so containers are designed to run on physical servers,virtual machines and any cloud instances.



Difference between containerization and virtualization
-->Virtualization technology that allows us to have a multiple operating system to share a single hardware processor

-->Containerization is an application-specific  virtualization ,because it provides an application with dedicated environment in the form of 
containers to run on, which can be deployed and run anywhere without a dedicated virtual machine with operating system for each application.


Also container was designed to solve modern problems and application management issues.so it's not a replacement for virtualization but its complementary to it.


Advantages of containers:
->containers are isolated doesn't require operating system and its shares a host kernel.
so,containers run on the same server and use the same resources,they don not interact with each other because its isolated .
if one application crashes,other containers with the same application will keep running without any issues.

->Its a portable and light weight operating system and it contains only the required binaries ,dependencies and libraries to run the application
so it compatiblity dependencies kind of issues.

->Faster and resources efficiency- its very fast to boot ,because containers are light weighted and start in less than second since they do not  a require an operating system boot

->Resource efficency since containers do not a require a seperate operating system,they use less resource

->improve scalablity- and lower costs.By allowing more containers in the environment without the need for more servers,containerization increases 
scalablity anywhere form1-0 to 100 times of that of traditional environments.

Introduction to docker:-What is docker on container?
->docker is a opensource platform tool designed to manage the containers,which allows us to build the application in a container with required libraries,dependencies to run the 
application,ship the container and run anywhere
eX:Docker,Kubernetes,Openshift,Amazon EKS,Google container engine,Azure Kubernetes Service


Introduction to docker-Why do we use Docker?
1)portablity->An applications can be bundled in to a single unit and same unit can be deployed to various environments such as dev server,testing server,and production server without making anychanges to container.
2)Light Weight-Docker Containers are pretty lightweight so,it provides a smaller footprint of the operating system via containers
3)fast delivery and scalable->Since Dockeer containers are light weight ,so they can be deployes faster and that they are very easily scalable.
4)Docker used for contious deployment and testing.so with the help of containers,it becomes easier for teams across different units such as developmenr,QA and operations to wrok seamlessly across applications
5)Docker also provides you ,ability to run multiple isolated os an single hosts
6)Resource Optimization:Docker enable you to utilize the maximum resources and reduce the resource wastages of your hardware



Docker Architecture and components

docker Client->Docker build,docker pull,docker run
Docker host ->Docker daemon ->containers,images  
Docker registry->docker hub

Docker installation  -> https://docs.docker.com/desktop/install/windows-install/

