#!groovy
pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                //echo 'Building..'
                bat 'gradle clean build'
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
