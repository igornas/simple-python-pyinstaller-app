pipeline {
  agent any
  stages {
    stage('BuildRoot') {
      steps {
        dir('/home/w/GitHub'){
          sh 'rm -rf simple-python-pyinstaller-app'
          sh 'git clone https://github.com/igornas/simple-python-pyinstaller-app'
        }  
      }
    }
  }
}
