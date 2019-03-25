#!groovy
pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                //echo 'Building..'
                //bat 'gradle clean'
                bat 'gradle build'
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
