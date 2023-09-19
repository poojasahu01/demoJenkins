pipeline{
    agent any
       stages{
        stage('Build'){
            input{
                message  "show we continue"
                ok "Yes we should"
            }
            steps{
                echo "Build stage"
            }
        }
        stage("Test deploy"){
            steps{
                echo12 "Test Deployment"
                
            }
        }
       }   
        post{
            always{
                echo "i will always run"
            }
            failure{
                echo "failed"
            }
            success{
                echo "success"
            }
            }
        }
        
    
