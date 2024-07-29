pipeline {
    agent any

    stages {
        stage('clone') {
            steps {
                sh "git clone https://github.com/andra2608/JenKinsTask.git"
            }
        }

        stage('Test') {
            steps {
                echo 'Testing...'
                // Your test steps go here
            }
        }
    }
}
