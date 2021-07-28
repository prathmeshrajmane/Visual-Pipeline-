pipeline {
  agent any
  stages {
    stage('Server') {
      agent any
      steps {
        sh '''echo "Building the server code"
mvn -version
mkdir -p target
touch "target/server.war"'''
      }
    }

  }
}