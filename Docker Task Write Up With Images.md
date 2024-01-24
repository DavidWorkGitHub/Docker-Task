# Docker-Task
Installation of Docker and Docker Compose: I began by installing Docker and Docker Compose on the target system following the official documentation provided by Docker.


Creation of Docker Compose File: A docker-compose.yml file was meticulously crafted to define the configuration of the Nginx, WordPress, and MySQL services. This file encapsulates the necessary parameters, such as images, container names, volumes, and ports.


Command Line Execution: Using the terminal, I navigated to the directory containing the docker-compose.yml The docker-compose up -d command was executed to initiate the creation and deployment of the Docker containers in detached mode.


Verification of Running Containers: The docker ps command was employed to verify the successful deployment of the containers. This command displays a comprehensive list of running containers, ensuring the integrity of the environment.


Accessing the WordPress Site: The WordPress site became accessible through a web browser by navigating to http://localhost. This step confirmed the proper functioning of the Dockerized WordPress environment.
Termination of Containers: To conclude the deployment, the docker-compose down command was executed in the terminal. This step gracefully stopped and removed the containers, ensuring a clean shutdown of the Dockerized environment.


The implementation of the Dockerized WordPress environment proved to be a successful and efficient approach. Docker containers provide an isolated and reproducible environment, facilitating ease of a deployment, and maintenance.


![Docker 1](https://github.com/DavidWorkGitHub/Docker-Task/assets/65865159/4104ea06-037f-40d4-a550-4c932f5465f6)


![Docker 2](https://github.com/DavidWorkGitHub/Docker-Task/assets/65865159/3f60198d-8ae9-472a-ae36-0b92ea9fdd36)


![Docker 3](https://github.com/DavidWorkGitHub/Docker-Task/assets/65865159/53f01f3d-2be2-4a80-bddb-af7d9eec3e3c)


![docker port](https://github.com/DavidWorkGitHub/Docker-Task/assets/65865159/b119666f-ee98-4889-bd72-ae29338d7f1a)
