pipeline {
  agent any
  stages {
    stage('echo') {
      agent any
      steps {
        sh 'echo "$PWD"'
        sshagent(ignoreMissing: true) {
          sh 'echo test'
        }
        
      }
    }
  }
}