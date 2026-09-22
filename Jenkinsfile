pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Build successful'
            }
        }

        stage('Test') {
            steps {
                echo 'Tests passed'
            }
        }

        stage('Deploy') {
            steps {
                echo 'Deploy successful'
            }
        }
    }

    post {
        success {
            echo 'Pipeline completed successfully!'
        }
    }
}
