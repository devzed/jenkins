pipeline {
    agent { 
        node {
            label 'docker-agent-python3'
            }
      }
    triggers {
        pollSCM '*/3 * * * *'
    }
    stages {
        stage('Build') {
            steps {
                echo "Building.."
                sh '''
                echo "Doing something else"
                '''
            }
        }
        stage('Test') {
            steps {
                echo "Testing.."
                sh '''
                echo "Doing something else"
                '''
            }
        }
        stage('Deliver') {
            steps {
                echo 'Deliver..'
                sh '''
                echo "Doing something else"
                '''
            }
        }
    }
}