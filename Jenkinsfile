pipeline {
    agent any
    stages {
        stage('build') {
            steps {
                sh 'pwd'
                sh 'ls -la'
                sh 'ls /var'
                sh 'ls /home'
                sh 'php -v'
                sh 'java -version && javac -version'
                sh 'docker -v && docker-compose -v'
            }
        }
    }
}
