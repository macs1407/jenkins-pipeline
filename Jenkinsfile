@Library('jenkinsLib')
pipeline {
    agent any

    stages {
        stage('clona') {
            steps {
                script {
                    dockerLib.clonar(nombreRepo: "matias")
                }
            }
        }
        stage('compilando') {
            steps {
                echo 'Mvn clean installl ...............'
            }
        }
        stage('desplegando') {
            steps {
               script {
                    dockerLib.publicando(version: "1.0")
                }
            }
        }
    }
}
