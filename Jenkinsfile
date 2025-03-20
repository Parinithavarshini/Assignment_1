pipeline {
    agent any
    stages {
        stage('Clone Repository') {
            steps {
                script {
                    git branch: 'main', credentialsId: 'GitHub_Credentials', url: 'https://github.com/Parinithavarshini/Assignment_1.git'
                }
            }
        }
        stage('Build') {
            steps {
                echo 'Building...'
            }
        }
    }
}
