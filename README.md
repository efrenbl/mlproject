[![efrenbl](https://circleci.com/gh/efrenbl/mlproject.svg?style=svg)](https://app.circleci.com/pipelines/github/efrenbl/mlproject)

## Project Overview

This project execute a mi microservices builded with **Scikit-Learn**. You can check the training data in https://www.kaggle.com/c/boston-housing.


### How to use this repository?

1.- Fork and clone in your local machine

2.- Setup with `make setup` command. 

3.- Install dependencies with `make install` command

4.- Run the app with `./run_docker.sh` command

5.- If you want to upload the docker image use the `./upload_docker.sh` command, just don't forget to replace the dockerpath with your docker user.

6.- Run `./run_kubernetes.sh` command to deploy to kubernetes 


### Requirements
1.- Python 3.7

2.- Minikube

3.- Docker

4.- Kubectl
