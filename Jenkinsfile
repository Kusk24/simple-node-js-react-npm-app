pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                script {
                    docker.image('node:lts-alpine').inside {
                        sh 'npm install'
                    }
                }
            }
        }
    }
}
