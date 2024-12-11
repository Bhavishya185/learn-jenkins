pipeline {
    agent any 
    stages {
        stage('Build') { 
            steps {
               script{
                 sh "This is Build"
               }
            }
        }
        stage('Test') { 
            steps {
                script{
                   sh "This is test"
               }
            }
        }
        stage('Deploy') { 
            steps {
                script{
                   sh "This is deploy"
               }
            }
        }
    }
}