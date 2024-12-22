pipeline {
    agent any
    stages{
        stage("intro") {
            steps{
            
                sh 'echo Printing system deatils'
                
            }
        }
        stage("system memory details") {
            steps {
                
                sh 'free'
                sh 'nproc'
                
            }
        }
        stage("cpu details") {
            steps{
                
                sh 'lscpu'
                
            }
        }
    }
}
