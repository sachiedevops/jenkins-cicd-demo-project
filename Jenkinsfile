pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building website'
            }
        }

        stage('Test') {
            steps {
                echo 'Testing website'
            }
        }

        stage('Deploy') {
            steps {
                sh 'cp index.html /var/www/html/index.html'
                echo 'Website deployed successfully!'
            }
        }
    }
}
