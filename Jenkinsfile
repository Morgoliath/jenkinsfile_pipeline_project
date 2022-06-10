pipeline {
    agent any
    stages {
        stage('build') {
            steps {
                echo 'Compiling the java source code'
                sh 'javac Hello.java'
            }
        }
        stage('run') {
            steps {
                echo 'Running the compiled java code.'
                sh 'java Hello'

            }
        }
        stage('test') {
            steps {
                echo 'Morgoliathway to Reinvent Yourself'
                sh "echo Hello Turker!"
            }
        }
    }
}
