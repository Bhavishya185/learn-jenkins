pipeline {
    agent any {
        label 'AGENT-1'
    }
    stages {
        stage('Build') { 
            steps {
            
                sh 'echo This is Build'
               
            }
        }
        stage('Test') { 
            steps {
                
                   sh 'echo This is test'
               
            }
        }
        stage('Deploy') { 
            steps {
                
                   sh 'echo This is deploy'
                //    error 'pipeline failed'
               
            }
        }
    
    }

    post {
        always {
            echo "This section runs always"
        }
        success{
            echo "This section run when pipeline success"
        }
        failure {
            echo "This section run when pipeline failure"
        }
    }
}