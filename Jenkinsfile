pipeline {
    agent any

    stages {
        stage('Create a directory') {
            steps {
                sh 'mkdir arsene'
            }
        }

        stage('Create a file') {
            steps {
                script {
                    sh '''
                    touch arsene/text.txt
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

