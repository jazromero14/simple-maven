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

    stage('Test2') {
      steps {
        sh 'echo \'Hello world 2.0\''
      }
    }

    stage('Test3') {
      steps {
        sh 'echo \'Hello world 2.1\''
      }
    }

  }
}