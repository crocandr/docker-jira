# Jira in Docker

This is a basic Jira stack in Docker.

## Prerequisites 

Create data folder for Jira and set the permission.

```
mkdir data
chmod 777 data
```

or change the data folder permission after the first start as soon as possible.

## Run

```
docker-compose up -d
```

You have to wait some minutes (4-10) after the first start while the MySQL and Jira creating the DB.

## Setup

Open the http://your_docker_host:8080 (example: http://192.168.56.101:3000) in your browser and follow the wizzard's steps.

You have to register and buy a license key on https://my.atlassian.com or start a short trial period (some days).

## More information

Check the source repositories for more information:
  - https://hub.docker.com/r/blacklabelops/jira/
  - https://github.com/blacklabelops/jira
  - https://hub.docker.com/_/mysql/

 
