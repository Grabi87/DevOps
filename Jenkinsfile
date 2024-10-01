pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                script {
                    bat 'docker pull nginx'  // Este comando es un ejemplo
                    bat 'docker run -d --name mi_contenedor -p 8080:80 nginx'
                }
            }
        }
    }
}
