pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building..'
                sh 'composer create-project drupal/recommended-project'
            }
        }
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
