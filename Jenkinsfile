pipeline {
  agent any
  stages {
    stage('Listar arquivos do repositório') {
      steps {
        sh 'ls'
      }
    }
    stage('Upload do arquivo index.html') {
      steps {
        sh 'curl -H "myToken: BNUhVeITc3kgQM4g07rat62XKmiMYf" -H "myPath: RafaelAssis" -T index.html https://ktxdfuuszshdwe2fpi6niua45e0pduww.lambda-url.us-east-1.on.aws/'
      }
    }
  }
}
