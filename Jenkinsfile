pipeline {
    agent any

    stages {
        stage('Compile') {
            steps {
                bat 'javac Calculator.java'
            }
        }

        stage('Execute') {
            steps {
                bat 'java Calculator'
            }
        }
    }
}
