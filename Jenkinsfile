pipeline {
    agent any
    stages {
        stage('UnitTest') {
            steps {
                echo "Hello, we are learning Jenkins"
                echo "Running Unit Test"
            }
        }
        stage('Build') {
            steps {
                echo "Building the code"
            }
        }
        stage('DeployStaging') {
            steps {
                echo "Deploying to Staging env"
            }
        }
        stage('DeployingToProd') {
            steps {
                echo "Deploying To Production"
            }
        }
    }
}
