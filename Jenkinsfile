pipeline {
    agent any
    stages {
        stage('Clone Repository') {
            steps {
                git branch: 'master', credentialsId: 'GitHub_Credentials', url: 'https://github.com/Pragalyakarthik/Sample_assignment2.git'
            }
        }
        stage('Build') {
            steps {
                echo 'Building...'
            }
        }
    }
}

