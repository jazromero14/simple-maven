pipeline {
  agent any
  stages {
    stage('build') {
      steps {
        sh 'mvn package'
      }
    }

    stage('Test') {
      steps {
        sh 'mvn test'
      }
    }

    stage('Delivered') {
      steps {
        sh 'sudo ./jenkins/scripts/deliver.sh'
      }
    }

  }
}