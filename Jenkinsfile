pipeline {
    agent any 
    stages {
        stage('Build') { 
            steps {
                bat 'javac jenkinstutorials/printseries.java'
            }
        }
        stage('Test') { 
            steps {
                bat 'cd jenkinstutorials'
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
