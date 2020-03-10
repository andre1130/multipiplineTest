@Library('Common@master') _ 

pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building..'
                HelloWorld 'hello ali'
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
