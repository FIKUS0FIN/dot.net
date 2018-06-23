pipeline {
  agent {
    docker {
      image 'busybox'
    }
    
  }
  stages {
    stage('echo') {
      agent any
      steps {
        sh 'echo "$PWD"'
      }
    }
  }
}