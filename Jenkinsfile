pipeline {
    agent any
    stages {
        stage('Build app') {
            steps {
                bat 'dotnet build'
            }
        }
        stage('Run tests') {
            steps {
                bat 'dotnet test'
            }
        }
    }
}
