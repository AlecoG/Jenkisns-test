// Jenkinsfile (ejemplo básico)
pipeline {
    agent {label 'laptop-ale-linux'} 
    
    stages {
        stage('Checkout') {
            steps {
                checkout scm  // Automáticamente clona el repo que contiene este Jenkinsfile
            }
        }
        
        stage('Build') {
            steps {
                sh 'echo "Este es un build de ejemplo usando código de GitHub"'
                sh 'python3 main.py'
                sh 'ls -la'
                sh 'echo Terminado pipeline con exito'
            }
        }
    }
}
