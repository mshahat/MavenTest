pipeline {
  agent {
    docker {
      image 'maven'
    }
    
  }
  stages {
    stage('maven-clean') {
      steps {
        sh 'mvn clean'
      }
    }
  }
}