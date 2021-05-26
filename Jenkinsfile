pipeline {
    agent any
    stages {
        stage ('Início') {
            steps {
                bat 'echo inicio'
            }
        }
        stage ('Meio') {
            steps {
                bat 'echo meio'
                bat 'echo meio de novo'
            }
        }
        stage ('Fim') {
            steps {
                sleep(8)
                bat 'echo fim!'
            }
        }
    }
}