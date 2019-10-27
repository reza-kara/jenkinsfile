pipeline {
        agent any
        environment { 
                CC = 'clang'
        }
        stages {
                stage('Example'){
                    steps{
                        echo env.JENKINS_URL
                        echo env.CC
                        echo "Running ${env.BUILD_ID} on ${env.JENKINS_URL}"
                        echo "hello world"
                    }
                }
        }
}
