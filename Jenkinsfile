pipeline {
    agent { any }
    stages {
        stage('build') {
            steps {
                sh 'echo hello4'
                sh 'docker-compose up -d'
                sh 'docker-compose down'
            }
        }
    }
}
