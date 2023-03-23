pipeline {
  agent any
  stages {
    stage('Deployment') {
      steps {
        echo 'i want to develop'
      }
    }

    stage('Test') {
      parallel {
        stage('Test') {
          steps {
            echo 'i want to test'
          }
        }

        stage('deploy') {
          steps {
            echo 'i want to deploy the code'
          }
        }

      }
    }

  }
}