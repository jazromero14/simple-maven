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
        sh 'echo \'Hello world\''
      }
    }

  }
}