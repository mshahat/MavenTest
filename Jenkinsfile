pipeline {
  agent any
  stages {
    stage('build') {
      steps {
        sh '''cd BWCEMavenTest/ChrisDockerRestTemplate.application.parent
mvn clean'''
      }
    }
  }
}