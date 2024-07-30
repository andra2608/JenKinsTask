pipeline {
    agent any

    stages {
        stage('clone'){
            steps{
                git branch:'develop' url: 'https://github.com/andra2608/JenKinsTask.git'

                dir('E:\\GIT\\git_practice'){
                    script {
                        bat 'git config --global --add safe.directory E:\GIT\git_practice'
                        bat 'git pull origin develop'
    }
}
