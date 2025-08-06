pipeline {
    agent any

    tools {
        jdk 'JDK17'
    }

    stages {
        stage('Build') {
            steps {
                echo 'Building the project...'
                sh 'javac -version'
            }
        }
        stage('Test') {
            steps {
                echo 'Running tests...'
                // Add your test commands here
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying application...'
            }
        }
    }
}
