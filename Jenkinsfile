pipeline {
    agent {
    node {
        label 'AGENT-1'
    }
    environment { 
        COURSE = 'jenkins'
}

    stages {
        stage('Build') {
            steps {
                script{
                    sh """
                      echo "Building.."
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
}