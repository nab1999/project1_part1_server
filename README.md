# DevOps Capstone Project – 01 (PART 1: Server)
## Part 1: Application and Container Building for Server

### 1.0 Creating a new directory for this project called “project1”, where all the files related to our work will be stored.

![image](https://github.com/nab1999/project1_part1_server/assets/126570628/fd802363-548b-47b2-8354-ef97484a6bbe)

### 1.1 Server:
Making a separate directory for the server, to store its relative files.

![image](https://github.com/nab1999/project1_part1_server/assets/126570628/e99b3d61-3f8a-4e28-aa0f-3815070f1b60)

#### 1.1.1 Creating a Dockerfile for server container:

![image](https://github.com/nab1999/project1_part1_server/assets/126570628/7b059abd-cb9b-40ed-8489-2795e42fc36d)

#### Dockerfile:

![image](https://github.com/nab1999/project1_part1_server/assets/126570628/a39add06-b4ed-4711-8413-a5ea63b8711b)

#### 1.1.2 Creating a server application using python:

![image](https://github.com/nab1999/project1_part1_server/assets/126570628/59af7827-9315-4160-a542-03e4240fa178)

#### 1.1.3 Creating a “docker-compose.yml” YAML file to use docker compose for defining and running the server container:

![image](https://github.com/nab1999/project1_part1_server/assets/126570628/a837bf53-c7f5-4f41-82dc-0c05903ae2bf)

#### 1.1.4 Running the server container: 
To run the server, we will navigate to the directory containing the above files and run “docker-compose up -d” command. This will build the Docker image, start the container, and expose port 8080 to the host machine.

![image](https://github.com/nab1999/project1_part1_server/assets/126570628/5dccacf7-6bb5-4da2-a3d9-b9bb7a493f70)

#### Container created:

![image](https://github.com/nab1999/project1_part1_server/assets/126570628/03372ec5-675a-4e00-aa53-10e7710ebd6a)

#### Volume created in local machine for server container: 

![image](https://github.com/nab1999/project1_part1_server/assets/126570628/11f09c6f-8a42-492e-8c7d-3d779abf75e4)

#### Random text file present in both local and container volume (showing that they are shared between host & container):
Local volume:

![image](https://github.com/nab1999/project1_part1_server/assets/126570628/07b407c5-303d-4616-b6a3-1ffe8ae90af6)

Container Volume:

![image](https://github.com/nab1999/project1_part1_server/assets/126570628/e6720205-a551-48ff-8066-b3c3e5aaf4e3)

