pipeline {
  agent any
  stages {
    stage('clean') {
      steps {
        sh '''cd BWCEMavenTest/ChrisDockerRestTemplate.application.parent
mvn clean'''
      }
    }
  }
}