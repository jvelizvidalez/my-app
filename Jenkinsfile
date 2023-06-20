pipeline {
  agent any
  stages {
    stage('Build') {
      parallel {
        stage('Build') {
          steps {
            sh 'yarn install'
          }
        }

        stage('Build2') {
          steps {
            sh 'yarn build'
          }
        }

      }
    }

  }
}