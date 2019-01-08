# Setting up InterFlex VLab

## 1. Have you Docker ID registered

## 2. Install Docker

## 3. Run VLab

0. Run docker 
0. Open Docker CLI. On Windows this should/can be the Power Shell or Docker
0. Login with your Docker ID using the command

`docker login`

0 After succesully logging in, download the latest Docker-Compose configuration file from:

https://raw.githubusercontent.com/forinterflex/vlab-run/master/docker-compose.yml

0 Save the docker-compose.yml file in a directory of your choice.

0 Pull the base image

`docker pull forinterflex/vlab:ait-v0.1`

0 Finally, run the VLab

`docker-compose up`

from the diectroty where you have coppied the configuration file in Step 5.


