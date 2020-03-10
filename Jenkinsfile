@Library('Common@master') _ 

pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                HelloWorld 'hello'
            }
        }
        stage('Test') {
            steps {
                echo 'Testing..'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying....'
            }
        }
    }
}
