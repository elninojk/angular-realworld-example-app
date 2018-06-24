pipeline {
  agent {
    node {
      label 'test'
    }

  }
  stages {
    stage('1') {
      steps {
        timestamps() {
          echo 'done'
        }

      }
    }
  }
}