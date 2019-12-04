pipeline{
    agent any
    stages{
        stage("printenv"){
            steps{
                sh 'printenv'
                sh 'echo felipe'
                gerritReview message: "Hi"
            }
        }
    }
}