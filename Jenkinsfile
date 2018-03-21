pipeline {
  agent any
  stages {
    stage('Clone repo from GitHub') {
        dir('/home/w/GitHub'){
          sh 'rm -rf simple-python-pyinstaller-app'
          sh 'git clone https://github.com/igornas/simple-python-pyinstaller-app 
        }
    }
  }
}
