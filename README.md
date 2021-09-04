# Jenkins docker-compose installation

## Prerequisites

Make sure to have docker and docker-compose installed in your system.
If you have not docker installed you can get it at [Docker Download Page](https://docs.docker.com/get-docker/)


## Running the system

### Installation
Start by **forking** the repo
```bash
git clone https://github.com/Shadows97/jenkins-docker-compose.git
```

Now you can move to project root folder 
```bash
cd jenkins-docker-compose
```

Create `jenkins/` folder where the data will store at project root directory

You have to run this command only one time, for building the system an lauching it 
```bash
docker-compose up -d
```

this command will install 1 containers:
- jenkins


To launch the system, in the project directory, just do :

```bash
docker-compose start
```

To stop the system, in the project directory, just do :

```bash
docker-compose stop
```

To delete all the created containers do :

```bash
docker-compose down
```

To delete all the created containers, volumes and images do

```bash
docker-compose down -v --rm all
```

To see container logs

```bash
docker logs -f container_name
```

# Contributors

* M'PO Beniwo Charbel Derrick <mpoderrick97@gmail.com.com>"