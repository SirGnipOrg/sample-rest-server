pipeline {
   //agent { docker { image 'maven:3.5-alpine' } }
   agent any

   options {
      buildDiscarder(logRotator(numToKeepStr:'10'))
   }

   stages {
      stage('Build') {
         steps {
            echo 'testing a change to jenkinsfile 2'
            //sh 'mvn clean package'
         }
      }
   }
}
