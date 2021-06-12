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
      steps {
        sh 'docker -v'
      }
    }

  }
}