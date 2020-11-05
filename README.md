DEVOPS: Docker / Prestashop
===========================

Docker compose stack to easily install Prestashop

Installation
------------

First, you need to install docker on your computer: [https://docs.docker.com/get-docker/](https://docs.docker.com/get-docker/).

Then retrieve the docker compose file shared in this git repository: [https://raw.githubusercontent.com/konandrum/devops-docker-prestashop/main/docker-compose.yaml](https://raw.githubusercontent.com/konandrum/devops-docker-prestashop/main/docker-compose.yaml)

Now you can deploy the docker-compose stack like this:
```sh
$ docker-compose up -d path/to/the/docker-compose.yaml
```

You should have 2 more containers running on your docker engine.


How to access the Prestashop web application
--------------------------------------------

As you can see in the docker-compose file, the application is running over the `8069` port.

So simply open a browser, and go to the following url: [http://localhost:8069](http://localhost:8069)

You can change the allocated port if this one is already used.