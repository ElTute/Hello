pipeline {
  agent any
  stages {
    stage('print') {
      steps {
        sh '''
          echo ${message}
        '''
      }
    }
  }
  environment {
    message = 'World'
  }
}
