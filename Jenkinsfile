pipeline {
    agent any
    stages {
        stage('build') {
            steps {
                sh 'python3 --version'
            }
        }
        stage('run') {
            steps {
                sh 'python3 hello.py'
            }
        }
    }
}
