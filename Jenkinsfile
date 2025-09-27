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
               sh 'echo "This is"'
            }
        }

        stage("hotfix") { 
             steps { 
                sh 'echo "This is from H just to check  "'
            }
        }  
    }
}
