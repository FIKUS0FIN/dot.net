pipeline {
  agent {
    docker {
      image 'busybox'
    }

  }
  stages {
    stage('echo') {
      agent {
        docker {
          image 'busybox'
        }

      }
      steps {
        sh 'echo "$PWD"'
      }
    }
  }
}