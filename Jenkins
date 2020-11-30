pipeline {
    agent any 
    stages {
        stage('Build') { 
            steps {
                bat 'javac C:/Users/NAGARAJAN/Desktop/print/printseries.java'
            }
        }
        stage('Test') { 
            steps {
                bat 'cd C:/Users/NAGARAJAN/Desktop/print'
                bat 'java printseries'
            }
        }
        stage('Deploy') { 
            steps {
                print("java succssfulll")
            }
        }
    }
}
