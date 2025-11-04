pipeline {
    agent {
        label 'AGENT-1'
    }
    environment { 
        COURSE = 'jenkins'
    }
    //build
    stages {
        stage('Build') {
            steps {
                script{
                    sh """
                        echo "Hello build"
                        env
                    """
                }
            }
        }
        stage('Test') {
            steps {
                script{
                    echo 'testing..'
                }
            }
        }
        stage('Deploy') {
            steps {
                script{
                    echo 'Deploying..'
                }
            }
        }
    }
}
