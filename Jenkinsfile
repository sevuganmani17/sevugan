pipeline {
  agent any
  stages {
    stage('Test') {
      steps {
        sh 'echo "Test the script"'
      }
    }

    stage('Deploy') {
      steps {
        sh 'echo "deploy the script"'
      }
    }

    stage('Prod') {
      steps {
        sh 'echo "Move to production"'
      }
    }

  }
}