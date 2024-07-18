pipeline {
    agent any

    stages {
        stage('Initialize') {
            steps {
                echo 'Starting the build process.'
            }
        }
        
        stage('Build') {
            steps {
                // Assuming you're using a typical Java project with Maven. Change this to your build command.
                echo 'Building the application...'
            }
        }
        
        stage('Test') {
            steps {
                // Change this to your testing command.
                echo 'Testing the application...'
            }
        }
        
        stage('Deploy') {
            steps {
                // Add your deployment script here.
                echo 'Deploying the application...'
                // Example: sh './deploy.sh'
            }
        }
    }
    
    post {
        always {
            echo 'This will always run regardless of the result.'
        }
        
        success {
            echo 'Build was a success!'
        }
        
        failure {
            echo 'Build failed.'
        }
    }
}
