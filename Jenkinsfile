pipeline {
    agent any 
    stages {
        stage('Build') { 
            steps {
                bat 'git clone https://github.com/sudhakaran1995/jenkinstutorials.git'
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
