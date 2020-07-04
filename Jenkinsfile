pipeline {
 agent any
 stages {
 stage('shr-docker') {
     steps {
               sh "docker build -t shr:v1 ."
               sh "docker run -d -p 7777:80 shr:v1"
           }
                             }
   }
}
