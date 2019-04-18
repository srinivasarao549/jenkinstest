pipline {
  agent {
    docker {
      image 'node:8.15.1-alpine'
    }
  }
  stages {
    stage('build') {
      steps {
        sh 'npm --version'
      }
    }
  }
}