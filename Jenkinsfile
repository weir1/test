pipeline {
  agent {
    node {
      label 'maven_slave'
    }

  }
  stages {
    stage('Deploy') {
      steps {
        retry(count: 3) {
          echo 'hello'
          timeout(time: 3) {
            sleep 5
          }

        }

      }
    }

  }
}