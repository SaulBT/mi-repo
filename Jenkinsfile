 pipeline {
    agent any
    stages {
        stage('Clonar código') {
            steps {
                git 'https://github.com/SaulBT/mi-repo.git'
            }
        }
        stage('Compilar') {
            steps {
                sh 'echo "Compilando el proyecto..."'
            }
        }
        stage('Pruebas') {
            steps {
                sh 'echo "Ejecutando pruebas..."'
            }
        }
    }
 }
