pipeline {
  agent {
    docker {
      image 'centos'
    }

  }
  stages {
    stage('Build') {
      steps {
        sh 'cat /etc/centos-release'
      }
    }

    stage('Deploy') {
      steps {
        sh 'cat /etc/centos-release'
      }
    }

  }
  options {
    newContainerPerStage()
  }
}