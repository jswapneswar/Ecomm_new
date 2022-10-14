pipeline {
  agent any
  stages {
    stage('Checking tools') {
      steps {
        sh '''git --version
mvn --version
java --version'''
      }
    }

  }
}