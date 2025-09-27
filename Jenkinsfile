pipeline {   
    agent any

    stages {   
        stage('Master') { 
            steps { 
               sh 'echo "This is from master"' 
            }
        }
     
        stage('sprint1') { 
            steps { 
               sh 'echo "This is from S just to chcek"'
            }
        }

        stage("hotfix") { 
             steps { 
                sh 'echo "This is"'
            }
        }  
    }
}
