pipeline {
    agent any
    stages {
        stage('Prepare'){
            steps {
                git credentialsId: 'jenkins_1',
                    branch: 'main',
                    url: 'https://github.com/happyCat-KR/jenkins_first.git'
            }
        }
        stage('test') {
            steps {
                echo 'test stage'
            }
        }
        stage('build') {
            steps {
                echo 'build stage'
            }
        }
        stage('docker build') {
            steps {
                echo 'docker build stage'
            }
        }
    }
}