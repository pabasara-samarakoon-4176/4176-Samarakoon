pipeline {
    agent any
    stages {
        stage("Checkout") {
            steps {
                
                checkout scm
            }
        }

        stage("Test"){
            steps{
                sh 'npm --version'
            }
        }

        stage("Build"){
            steps{
                sh 'npm run dev'
            }
         } 
    }
    
}
