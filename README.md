Docker compose to get all flowable ui apps

# Prerequisites

- Docker
- Docker compose

https://hub.docker.com/u/flowable/

# How to run

Clone this repo to your local machine and run de containers with the default configuration in .env with the following command:

```
docker-compose up
```

This command will create the containers using latest flowable version and you will be able to login with username 'admin' 
and password 'test'.

Important: changing the admin password is not possible at this moment because this [Issue #1](https://github.com/frnd/flowable-ui-apps/issues/1)

# Services provided

https://sketchboard.me/NA2mTv5pmSMt#/

## Flowable IDM

[http://localhost:8080/flowable-idm](http://localhost:8080/flowable-idm)

## Flowable Modeler

[http://localhost:8080/flowable-modeler](http://localhost:8080/flowable-modeler)

## Flowable Task

[http://localhost:8080/flowable-task](http://localhost:8080/flowable-task)

## Flowable Admin

[http://localhost:8080/flowable-admin](http://localhost:8080/flowable-admin)

## Flowable Rest

[http://localhost:8080/flowable-rest/docs/](http://localhost:8080/flowable-rest/docs/)
