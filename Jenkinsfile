pipeline {
  agent {
    docker {
      image 'maven'
    }
    
  }
  stages {
    stage('maven-build') {
      steps {
        sh 'mvn clean'
      }
    }
  }
}