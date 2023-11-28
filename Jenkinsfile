pipeline {
    agent any

    stages {

        stage('Test') {
            steps {
                echo 'Testing..'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying....'
            }
        }  
        stage('Code Quality Check') {
            steps {
                sh 'phpcs --standard=PSR2 index.php'
            }
        }
        // Other stages in your pipeline

    }
}
