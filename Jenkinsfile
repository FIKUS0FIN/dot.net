pipeline {
  agent {
    docker {
      image 'busybox'
    }

  }
  stages {
    stage('echo') {
      steps {
        sh 'echo "$PWD"'
      }
    }
  }
}