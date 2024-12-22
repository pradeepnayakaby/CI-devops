pipeline{
    agent any
    stages[
        stage("intro"){
            steps{
                sh '''
                echo "Printing system deatils
                '''
            }
        }
        stage("system memory details"){
            steps{
                sh '''
                free
                '''
            }
        }
        stage("cpu details"){
            steps{
                sh '''
                lscpu
                '''
            }
        }
    ]
}