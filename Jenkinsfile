pipeline{
    agent any
    stages{
        stage("Git Checkout"){
            steps{
                git credentialsId: 'GitPass', url: 'https://github.com/sonaibabi/Git.git'
            }
            
        }
    }
}