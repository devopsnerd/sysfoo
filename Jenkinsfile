pipeline{
    
    agent any

// Add the tools and uncomment the following lines by removing /* and */ to enable the block. 
/*    tools{
    
    }
*/    
    stages{
        stage('one'){
            steps{
                echo 'this is first stage'
                sleep 4
            }
        }
        stage('two'){
            steps{
                echo 'this is second stage'
                sleep 9
            }
        }
        stage('three'){
            steps{
                echo 'this is third stage'
                sleep 7
            }
        }
    }
    
    post{
        always{
            echo 'the job is complete'
        }
        
    }
    
}
