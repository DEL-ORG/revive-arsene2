pipeline {
    agent any

    stages {
        stage('create a dir') {
            steps {
                sh '''
                mkdir arsene
                rm -rf arsene
                '''
            }
        }


        
        stage('create a file') {
            steps {
                sh '''
                touch text.txt
                rm -rf text.txt
                '''
                
            }
        }

        
    }
