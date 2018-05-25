# Build Jenkins, gitbub, nodejs project


## Run docker Jenkins
docker container run --rm --name jenkins -p 8080:8080 --volume `pwd`/jenkins:/var/jenkins_home jenkins/jenkins:lts

