pipeline {
    agent { docker { image 'php:8.3.2-alpine' } }
    stages {
        stage('build') {
            steps {
                sh 'php --version'
                sh 'echo "TEST PIPELINE"'
            }
        }
    }
}
