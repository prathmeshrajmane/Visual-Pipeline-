pipeline {
  agent {
    docker {
      image 'maven:3.5.0'
    }

  }
  stages {
    stage('Build') {
      steps {
        sh 'mvn compile'
      }
    }

    stage('Test') {
      steps {
        sh 'mvn clean test'
      }
    }

    stage('deploy') {
      steps {
        sh 'mvn package'
      }
    }

  }
}