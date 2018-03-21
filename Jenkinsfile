pipeline {
  agent any
  stages {
    stage('BuildRoot') {
      steps {
        git(poll: true, url: 'https://github.com/igornas/simple-python-pyinstaller-app.git', branch: 'master')
      }
    }
  }
}