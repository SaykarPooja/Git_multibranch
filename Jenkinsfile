pipeline {   
    agent any

    stages {   
        stage('Master') { 
            steps { 
               sh 'echo "This is from master......to check "' 
            }
        }
     
        stage('sprint1') { 
            steps { 
               sh 'echo "This is slave to check "'
            }
        }

        stage("hotfix") { 
             steps { 
                sh 'echo "This is hostfix to check.....'
            }
        }  
    }
}
