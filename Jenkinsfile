pipeline {
    agent {
      docker
      {
        image 'python:3.5.1'
        args '--userns host --privileged'
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
