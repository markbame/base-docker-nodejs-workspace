A. To instantiate the docker container
 1. run docker-compose up -d workspace

B. To get verify docker container is running
 1. run docker ps

C. To get inside docker container
 1. run docker exec -it <dockerhash> /bin/bash
    * once inside, navigate to the configured volume in the docker-compose.yml  
