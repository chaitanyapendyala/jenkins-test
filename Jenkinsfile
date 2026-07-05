pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Starting build...'
                sh 'echo Building application'
            }
        }
    }

    post {
        success {
            echo 'Build completed successfully.'
        }
        failure {
            echo 'Build failed.'
        }
    }
}
