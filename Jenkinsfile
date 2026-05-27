pipeline {
    agent any

    stages {

        stage('Clone') {
            steps {
                echo 'Cloning Code'
            }
        }

        stage('Build') {
            steps {
                echo 'Building Application'
            }
        }

        stage('Deploy') {
            steps {
                sh '''
                sudo cp -r * /var/www/html/
                '''
            }
        }
    }
}
