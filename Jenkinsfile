pipeline{

    agent any

    stages{
        stage('Hello'){
            steps{
                echo 'Shri Ganesh'
            }
        }
        
        post{
            success{
                echo "Job sucessfully run"
            }
            failure{
                echo " SOmething went wrong while job running"
            }
        }
    }

}