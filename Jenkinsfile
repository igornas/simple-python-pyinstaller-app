pipeline {
  agent any
  stages {
    stage('BuildRoot') {
      steps {
        sh 'cd /home/w/GitHub'
        sh 'touch 1.txt'
        sh 'git clone https://github.com/igornas/simple-python-pyinstaller-app pypineline'
      }
    }
  }
}
