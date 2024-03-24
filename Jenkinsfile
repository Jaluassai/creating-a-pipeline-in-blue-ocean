pipeline {
  agent {
    docker {
      image 'alpine/socat'
    }

  }
  stages {
    stage('Build') {
      steps {
        sh 'npm install'
      }
    }

  }
}