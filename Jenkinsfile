pipeline{
    agent "m2"
    Stages{
        stage('clean'){
            steps{
                bat mvn clean
            }  
        }
        stage('compile'){
            steps{
                bat mvn compile
            }  
        }
        stage('test'){
            steps{
                bat mvn clean test
            }  
        }

    }
}
