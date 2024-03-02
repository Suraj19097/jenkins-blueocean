pipeline {
  agent any
  stages {
    stage('build') {
      parallel {
        stage('build') {
          steps {
            sleep 10
          }
        }

        stage('analysis') {
          steps {
            echo 'my'
          }
        }

      }
    }

    stage('test') {
      steps {
        sh '''pwd
'''
      }
    }

  }
}