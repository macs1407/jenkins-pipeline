pipeline {
    agent any

    stages {
        stage('clona') {
            steps {
                echo 'Clonando repo ...................'
            }
        }
        stage('compilando') {
            steps {
                echo 'Mvn clean installl ...............'
            }
        }
        stage('desplegando') {
            steps {
                echo 'deploy ...............'
            }
        }
    }
}
