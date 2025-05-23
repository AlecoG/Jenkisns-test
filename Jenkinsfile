// Jenkinsfile (ejemplo básico)
pipeline {
    agent any
    
    stages {
        stage('Checkout') {
            steps {
                checkout scm  // Automáticamente clona el repo que contiene este Jenkinsfile
            }
        }
        
        stage('Build') {
            steps {
                sh 'echo "Este es un build de ejemplo usando código de GitHub"'
                sh 'ls -la'
            }
        }
    }
}
