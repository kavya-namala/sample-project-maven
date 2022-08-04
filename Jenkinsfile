pipeline {
  agent any
  stages {
    stage('Test') {
      steps {
        fileExists 'pom.xml'
      }
    }

    stage('build') {
      steps {
        echo 'Maven Project'
      }
    }

  }
}