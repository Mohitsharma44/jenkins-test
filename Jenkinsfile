pipeline {
    agent {
      docker
      {
        image 'python:3.5.1'
        args '--user root --privileged'
      }
    }
    stages {
      stage('build') {
          steps {
              sh 'python --version'
          }
      }
  }
}
