# Docker & Docker Hub


### Assignment 1:

Demonstrate minimum 15 basic docker command with explanation and screenshot.

#### Docker Command 1

```
docker images
```
Command is used to list all the docker images available locally in your system.
![image](https://user-images.githubusercontent.com/70307607/194695304-c12e64c8-e837-4430-8e42-c80437f1ad43.png)

#### Docker Command 2
```
docker build -t arnabdas1993/hello-app .
```
It will create the docker image form **Dockerfile**. Here "-t" to provide name(arnabdas1993/hello-app) of the image.
![image](https://user-images.githubusercontent.com/70307607/194708132-a18776d7-094d-4841-ab00-093cd5188ddc.png)


#### Docker Command 3
```
docker run -d -p 5000:5000 hello-app
```
This commarnd used to run a docker image. Here "-d" means detached mode(runs in the background)
![image](https://user-images.githubusercontent.com/70307607/194708189-fbe303d7-3c5c-4123-b7ed-d697d427d1f8.png)
![image](https://user-images.githubusercontent.com/70307607/194708201-83191f0e-3661-49ba-ac4a-816fe63c20c2.png)
#### Docker Command 4
```
docker ps
```
Command is used to list all running containers locally in your system.
![image](https://user-images.githubusercontent.com/70307607/194708318-d397057d-7ced-41e1-ae42-4ae1c8f29a57.png)


#### Docker Command 5

```
docker stop d3b5c37eeabe
```
This command is used to stop a running container. Here "d3b5c37eeabe" is the running container Id
![image](https://user-images.githubusercontent.com/70307607/194708379-8e944d54-6d98-4cc1-8494-aaf3e2e3d6da.png)

#### Docker Command 6
```
docker push arnabdas1993/hello-app:latest
```
This Command used to push our local docker image to Docker Hub.
![image](https://user-images.githubusercontent.com/70307607/194708454-00910642-4ca2-4b90-8ff5-87c7ad6cc493.png)


#### Docker Command 7
```
docker ps -a
```
This command used get all available container in the local machine.
![image](https://user-images.githubusercontent.com/70307607/194708603-307f7fbb-26e2-49f6-971f-19aad6a6c006.png)


#### Docker Command 8

```
docker start d3b5c37eeabe
```
This Command used to start a docker container. Here "d3b5c37eeabe" is a Container Id
![image](https://user-images.githubusercontent.com/70307607/194708662-09a5a4f3-df6a-4183-83ca-1510566b5a48.png)

Similar to this, the below code will restart the container.
```
docker restart d3b5c37eeabe
```

#### Docker Command 9
```
docker pause d3b5c37eeabe
```
This Command used to pause a running container. After executing this, if we want to browse in the chrome we will get error.

![image](https://user-images.githubusercontent.com/70307607/194708842-375e2f38-0105-4f91-b391-ef9c2dcd4cd1.png)
```
docker unpause d3b5c37eeabe
```
This Command used to resume a paused container.
![image](https://user-images.githubusercontent.com/70307607/194708866-0be6d366-4823-4346-9061-f47a96377a61.png)

#### Docker Command 10
```
docker pull arnabdas1993/hello-app:latest
```
This Command used to pull the mentioned Docker Hub repositories.
![image](https://user-images.githubusercontent.com/70307607/194709096-dd1af48d-87f9-4f84-88b1-7f7cd081a73a.png)


#### Docker Command 11
```
docker rmi -f docker/getting-started
```
This command used to delete a Docker images from the local system
![image](https://user-images.githubusercontent.com/70307607/194709238-e9d437ca-f378-49d1-b709-cdb6bccb38c9.png)

#### Docker Command 12
```
docker kill d3b5c37eeabe
```
This Command used to kill a running container.
![image](https://user-images.githubusercontent.com/70307607/194755698-a677d6eb-85ce-419b-b501-486ad59a8c5c.png)

#### Docker Command 13
```
docker rm -f d3b5c37eeabe
```
This Command is used to destroy a container. Here, "-f" allows removing running containers
![image](https://user-images.githubusercontent.com/70307607/194755532-57fa91aa-3c39-42ec-929e-0633378feea2.png)


#### Docker Command 14
```
docker top 665c2c35e2ca 
```

This Command used to get the list the processes running inside a container. 
![image](https://user-images.githubusercontent.com/70307607/194755827-1b332500-18cc-4ff0-93c6-2c3f4472cdeb.png)

#### Docker Command 15
```
docker history arnabdas1993/hello-app
```
Command is used to see the history of a repository.
![image](https://user-images.githubusercontent.com/70307607/194695544-e1b87c0b-a9cd-42f3-af90-3e6d69099165.png)

### Assignment 2:

[Hello World Docker Image](https://hub.docker.com/_/hello-world)
Run Hello World Docker Image Locally.
```
## This command used to pull the docker hub repo.
docker pull hello-world

## This Command used to run the repo.
docker run hello-world 
```
![image](https://user-images.githubusercontent.com/70307607/194756120-bc3501f0-f785-4a3c-89a6-91d586aa7143.png)


### Assignment 3:
Create a hello world fastapi application.
Create a Dockerfile for your fastapi hello world application.
Build Docker image using Docker file.
Run docker image build in previous step.
Push your Docker image to Docker Hub.


```
docker build -t arnabdas1993/hello-fast-api . 
```
To build the docker images we use the above statement.
```
docker run -d -p 5000:5000 arnabdas1993/hello-fast-api
```
To run the docker images, we use the above command.
![image](https://user-images.githubusercontent.com/70307607/195492763-049cd47c-af42-41d5-833f-8b6e6609e402.png)

```
docker push arnabdas1993/hello-fast-api:latest
```
This is code to push the docker images to docker hub.
![image](https://user-images.githubusercontent.com/70307607/195493134-f900259f-e231-4995-943c-526b0be6b5a2.png)

You can find the images in [this link](https://hub.docker.com/repository/docker/arnabdas1993/hello-fast-api).

### Assignment 4:
Automate Assignment below task using github action.
1. Build Docker Image 
2. Push Docker Image to Docker hub.
