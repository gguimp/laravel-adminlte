pipeline {
  agent any
  stages {
    stage('checkout') {
      parallel {
        stage('checkout') {
          agent any
          steps {
            echo 'teste de mensagem'
          }
        }
        stage('testes') {
          steps {
            echo 'Olá'
          }
        }
      }
    }
    stage('outro') {
      steps {
        echo 'teste'
      }
    }
  }
}