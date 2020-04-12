pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building..'
                // copy everything to bucket
            }
        }
        stage('Test') {
            steps {
                echo 'Testing..'
                //  run tests
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying....'
                //  uploadaws s3
                sh 'aws s3 cp web/  s3://bbq-site-dev-bucket/ --recursive '

            }
        }
    }
}
