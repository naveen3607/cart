@Library('roboshop') _

pipeline {
    agent any
    stages {
        stage('Hello') {
            steps {
                echo 'Hello World'
                script {
                  demo.info 'Starting'
                  demo.warning 'Nothing to do!'
                }
            }
        }
        stage('Test') {
            steps {
                echo 'Hello World'
            }
        }
        stage('Code Quality') {
            steps {
                echo 'Hello World'
            }
        }
        stage('Code Security') {
            steps {
                echo 'Hello World'
            }
        }
    }
}