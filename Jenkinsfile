pipeline {
  agent none
  stages {
    stage('checkout') {
      agent any
      steps {
        git(url: 'https://github.com/docker-library/hello-world.git', branch: 'head')
      }
    }

  }
}