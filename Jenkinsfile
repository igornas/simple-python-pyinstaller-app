pipeline {
  agent any
  stages {
    stage('BuildRoot') {
      dir('/home/w/GitHub') {
        steps{
          sh 'rm -rf simple-python-pyinstaller-app'
          sh 'git clone https://github.com/igornas/simple-python-pyinstaller-app'
        }  
      }
    }
  }
}
