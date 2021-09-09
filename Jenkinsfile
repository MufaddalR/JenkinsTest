pipeline {
    agent any

    stages {
        stage('Dev') {
            steps {
                echo 'Hello World'
            }
        }
        stage('Build') {
            steps {
                build quietPeriod: 5, job: 'TestJob1'
            }
        }
        stage('Test') {
            steps {
                echo 'Hello World'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Hello World'
            }
        }
    }
}
