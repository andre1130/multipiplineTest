@Library('Common@master') _ 

pipeline {
    agent any
    
    parameters {

            choice(name: 'promote_to', choices: ['none', 'dev'], description: 'Deploy to ?')

            choice(name: "release_type", choices: "None\nHotfix\nPatch\nMinor\nMajor" , description: "Type of release for version increment")

            string(name: 'ttl', defaultValue: '1', description: 'Time to live - number of days before the env. is deleted. Default 1. Max 7')
    }
    stages {
        stage('Build') {
            steps {
                echo 'building'
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
