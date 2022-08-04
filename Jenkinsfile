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

    stage('Deploy') {
      steps {
        timestamps() {
          timestamps() {
            timeout(time: 3, unit: 'HOURS')
          }

        }

      }
    }

  }
}