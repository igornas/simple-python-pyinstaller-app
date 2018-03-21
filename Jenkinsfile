pipeline {
  agent any
  dir('/home/w/GitHub')
  stages {
    stage('BuildRoot') {
        steps{
          sh 'rm -rf simple-python-pyinstaller-app'
          sh 'git clone https://github.com/igornas/simple-python-pyinstaller-app 
        }
    }
  }
}
