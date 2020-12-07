pipeline {
    agent any 
    stages {
        stage('Build') { 
            steps {
                bat 'javac printseries.java'
            }
        }
        stage('Test') { 
            steps {
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
