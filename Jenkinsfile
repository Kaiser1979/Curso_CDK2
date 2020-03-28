pipeline {
  agent any
  stages {
    stage('Inicio') {
      steps {
        sh 'ls '
      }
    }

    stage('Builds') {
      parallel {
        stage('enviroment') {
          steps {
            sh 'env'
          }
        }

        stage('') {
          steps {
            sh 'note --version'
          }
        }

      }
    }

  }
}