pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                script {
                    bat 'docker pull nginx'
                    bat 'docker run -d --name mi_contenedor -p 8080:80 nginx'
                }
            }
        }
    }
}
