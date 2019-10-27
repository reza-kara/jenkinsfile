pipeline {
        agent any
        environment { 
                CC = 'clang'
        }
        parameters {
                string(name: 'Greeting', defaultValue: 'Hello', description: 'How should I greet the world?')
        }
        stages {
                stage('Example'){
                    steps{
                        echo env.JENKINS_URL
                        echo env.CC
                        echo "Running ${env.BUILD_ID} on ${env.JENKINS_URL}"
                            echo "${params.Greeting} World!"
                    }
                }
        }
}
