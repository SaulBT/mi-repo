 pipeline {
    agent any
    stages {
        stage('Clonar código') {
            steps {
                git branch: 'main', url:'https://github.com/SaulBT/mi-repo.git'
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
