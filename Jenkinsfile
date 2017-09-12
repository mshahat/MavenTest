pipeline {
  agent any
  stages {
    stage('maven-version') {
      steps {
        sh 'echo "mvn"'
      }
    }
    stage('maven-clean') {
      steps {
        build 'mvn --version'
      }
    }
  }
}