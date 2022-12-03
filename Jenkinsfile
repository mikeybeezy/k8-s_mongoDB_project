pipeline {
    agent any
    tools{
        maven 'Maven 3.8.6'
    }
    stages{
        stage('Deploy to kubernetes'){
            steps{
                script{
                    sh 'kubectl delete -f deployment-files'


                }
            }
        }
    }
    
}