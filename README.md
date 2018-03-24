# Gitlab-ce cluster setup with Docker-compose

Setup Gitlab-ce cluster (Gitlab-ce, Redis, Postgresql) & Jenkins with Docker-compose 

# Requirements

* Docker
* Docker-compose

# Installtion

* Clone the project
* Update `docker-compose.yml` if you want to change some configs.

```
$ docker-compose up -d
```
* **NOTE**: gitlab-ce http port: 10080, gitlab-ce ssh port: 10022, jenkins port: 49001
