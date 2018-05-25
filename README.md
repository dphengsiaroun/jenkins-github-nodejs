# Build Jenkins, gitbub, nodejs project

Ce tutoriel a pour but de faire une intégration de Jenkins avec Github, Node.js et Slack.

# Prerequisites

1. Installer Jenkins (https://jenkins.io/download/)
ou lancer cette commande pour démarrer un docker Jenkins
```
docker container run --rm --name jenkins -p 8080:8080 --volume `pwd`/jenkins:/var/jenkins_home jenkins/jenkins:lts
```
2. Installer Node (>8.1.0) (https://nodejs.org/en/).
3. Installer Slack (https://slack.com/intl/fr-fr/downloads/osx)
4. Créer un compte sur Github
5. Lien du projet à intégrer sur Jenkins (https://github.com/dphengsiaroun/jenkins-github-nodejs.git/)
6. Lien du tuto à suivre pour l'intégration (https://lethalbrains.com/integrating-jenkins-with-github-node-js-and-slack-e8fc4d2271b5)
