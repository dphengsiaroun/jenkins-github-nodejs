node {
   def commit_id
   stage('Preparation') {
     checkout scm
   }
   stage('install') {
     nodejs(nodeJSInstallationName: 'NodeJS9') {
       sh 'npm install ms -S'
     }
   }
   stage('test') {
     nodejs(nodeJSInstallationName: 'NodeJS9') {
       sh 'npm test'
     }
   }
}