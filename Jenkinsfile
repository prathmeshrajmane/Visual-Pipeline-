pipeline {
  agent none
  stages {
    stage('Build') {
      agent {
        docker {
          image 'nginx'
        }

      }
      steps {
        sh './new.sh'
      }
    }

  }
}