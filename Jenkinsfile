pipeline {
  agent any
  stages {
    stage('BuildRoot') {
      steps {
        sh 'rm -rf GitHub'
        sh 'mkdir GitHub'
        sh 'git clone https://github.com/igornas/simple-python-pyinstaller-app'
      }
    }
  }
}
