 pipeline {
    agent any
    stages {
        stage('Clonar código') {
            steps {
                sh 'echo "Clonando repo..."'
                git 'https://github.com/usuario/mi-repo.git'
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
