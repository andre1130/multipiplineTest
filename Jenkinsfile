@Library('Common@master') _ 

pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building..'
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
