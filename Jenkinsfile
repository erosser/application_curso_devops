pipeline {
  agent any
  stages {
    stage('Inicio_Envornment') {
      steps {
        echo 'Iniciando construccion de proyecto'
        sh 'env'
      }
    }

    stage('Docker Env') {
      parallel {
        stage('Docker Env') {
          steps {
            sh 'docker -v'
          }
        }

        stage('Images from docker') {
          steps {
            sh 'docker images'
          }
        }

      }
    }

  }
}