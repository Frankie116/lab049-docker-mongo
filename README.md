## -----------------------------------------------------------------------------------
# Project: DOCKER-profile-app-mongodb
## Purpose: Creates three interconnected docker containers which make up a sample app.
   Author: Frank Effrim-Botchey
## -----------------------------------------------------------------------------------


- Mongodb - standard container pulled from dockerhub
- Mongo-express - standard container pulled from dockerhub
- Custom - custom container built ontop of a node base which provides a simple user profile application. 

The docker image created is used by TF-fargate-using-cd-files project which spins up 2 fargate clusters hosting redundant loadbalanced versions of this app.



