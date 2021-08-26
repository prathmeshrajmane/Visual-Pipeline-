pipeline {
  agent none
  stages {
    stage('Build') {
      agent {
        docker {
          image 'nginx:latest'
        }

      }
      steps {
        sh 'sudo docker run -it --rm -d -p 8080:80 --name web nginx:latest'
      }
    }

  }
  options {
    newContainerPerStage()
  }
}