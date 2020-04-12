pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building..'
                sh 'ls -alh'
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
                //  upload everything to bucket
            }
        }
    }
}
