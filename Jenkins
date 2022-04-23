pipeline {
    agent any

    stages {
        stage('Git clone') {
            steps {
                echo 'cloning with git'
            }
        }
             stage('build') {
            steps {
                echo 'code is building'
            }
             }
             stage('Test') {
            steps {
                echo 'testing stage'
            }
             }
             stage('Deploy') {
            steps {
                echo 'deploying in server'
            }
             }
        }
}
