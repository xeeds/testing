pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                echo 'Building the project....'
                sh 'pwd' // Execute a shell command pwd
                sh 'ls -l' // Execute a shell command pwd
                sh 'more README.md' // Execute a shell command pwd
            }
        }
        stage('Test') {
            steps {
                echo 'Running tests...'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying the application...'
            }
        }
    }
    post {
        always {
            echo 'Pipeline finished.'
        }
    }
}
