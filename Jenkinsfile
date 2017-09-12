pipeline {
  agent {
    docker {
      image 'maven'
    }
    
  }
  stages {
    stage('maven-version') {
      steps {
        sh 'echo "mvn"'
      }
    }
    stage('maven-build') {
      steps {
        sh 'mvn clean'
      }
    }
  }
}