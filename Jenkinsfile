pipeline {
    agent any

    stages {
        stage('clone') {
            steps {
                echo 'Building'
            }
        }

        stage('Test') {
            steps {
                echo 'Testing...'
                // Your test steps go here
            }
        }
        stage('clone'){
            steps{
                git branch:'develop' url: 'https://github.com/andra2608/JenKinsTask.git'

                dir('E:\GIT\git_practice'){
                    script {
                        bat 'git config --global --add safe.directory E:\GIT\git_practice
    }
}
