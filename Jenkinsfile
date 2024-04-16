pipeline {
    agent any

    stages {
        stage('Create a directory') {
            steps {
                sh 'mkdir arsene' || true
            }
        }

        stage('Create a file') {
            steps {
                script {
                    sh '''
                    touch arsene/text.txt || true
                    '''
                }
            }
        }
        stage('Create a dir') {
            steps {
                script {
                    sh '''
                    mkdir thomas
                    '''
                }
            }
        }
    }
}

