pipeline {	
	agent {
		docker {
			image 'centos'
		}
	}
    options {	
        newContainerPerStage()
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
}
