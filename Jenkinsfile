pipeline {
  agent {
    docker {
      image 'nginx'
    }

  }
  stages {
    stage('Build') {
      steps {
        sh 'docker run -it --rm -d -p 8080:80 --name web nginx:latest'
      }
    }

  }
  options {
    newContainerPerStage()
  }
}