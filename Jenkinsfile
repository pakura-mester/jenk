pipeline {
	agent any 
	stages {
		stage('Build') {
			steps {
				echo 'building ${env.BUILD_ID} on ${env.JENKINS_URL}'	
			}
		}
        stage('Test') {
            steps {
                echo "testing ${env.BUILD_ID} on ${env.JENKINS_URL}"
            }
        }
        stage('Deploy') {
            steps {
                echo 'deploying...'
            }
        }
	}
}

