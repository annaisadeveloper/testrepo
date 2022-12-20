pipeline {
  agent none
  stages {
    stage('checkout') {
      steps {
        git(url: 'https://github.com/docker-library/hello-world.git', branch: 'head')
      }
    }

  }
}