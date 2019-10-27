pipeline {
	agent any
	environment { 1
		CC = 'clang'
	}
	stages {
		stage('Example'){
			def username = 'Jenkins'
			echo "Hello Mr. ${username}"
    			echo env.JENKINS_URL
			echo "Running ${env.BUILD_ID} on ${env.JENKINS_URL}"
    			echo "hello world"	
		}
	}
}
