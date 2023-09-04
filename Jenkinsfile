pipeline {
  agent any
  stages {
    stage('Checkout Code') {
      steps {
        git(url: 'https://github.com/m-ali-hasnain/mern-chat-app', branch: 'main')
      }
    }

    stage('shell') {
      steps {
        sh '''ls -la
'''
      }
    }

  }
}