//Pipeline Declarativo (siempre comienza por pipeline)
pipeline {
    // Ejecutar en cualquier agente (nodo)
    agent any
    
    //fases del trabajo
    stages {
        // fase individual (contenedor logico)
        stage('Build') {
            // Pasos de la fase
            steps {
                echo 'Building GIT...'
            }
        }
        
        stage('Test') {
            // Pasos de la fase
            steps {
                echo 'TESTING git...'
            }
    }
    stages {
        // fase individual (contenedor logico)
        stage('Deploy') {
            // Pasos de la fase
            steps {
                echo 'Deploying...'
            }
        }
    }
