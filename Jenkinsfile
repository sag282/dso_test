#!/usr/bin/env groovy

pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                echo 'Building...'
                bat 'build.bat'
                echo 'Built'
            }
        }
        stage('Test') {
            steps {
                echo 'Testing...'
                bat 'test.bat'
                echo 'Tested'
            }
        }
        stage('Deploy'){
            steps {
                echo 'Deploying...'
                bat 'deploy.bat'
                echo 'Deployed'
            }
        }
    }
}







