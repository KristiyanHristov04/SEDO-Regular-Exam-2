pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building .NET Application'
                bat 'dotnet build'
            }
        }
        stage('Run Unit and Integration Tests') {
            steps {
                echo 'Running tests'
                bat 'dotnet test'
            }
        }
    }
}