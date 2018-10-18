pipeline {
  agent any
  stages {
    stage('print') {
      steps {
        sh '''
          echo ${env.message}
        '''
      }
    }
  }
  environment {
    message = 'World'
  }
}
