pipeline {
   agent { docker { image 'maven:3.5-alpine' } }

   options {
      buildDiscarder(logRotator(numToKeepStr:'10'))
   }

   stages {
      stage('Build') {
         steps {
            echo 'testing a change to jenkinsfile'
            sh 'mvn clean package'
         }
      }
   }
}
