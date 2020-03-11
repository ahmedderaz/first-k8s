  
pipeline {
    agent any
	options {
	buildDiscarder logRotator(daysToKeepStr: '5', numToKeepStr: '6')
	}
    stages{
        stage('Build'){
            steps {
                echo 'Build'
            }
           
        }
        stage ('Deploy to Staging'){
            steps {
               echo 'Deploy-to-staging'
            }
        }

        stage ('Deploy to Production'){
            steps{
               

                
            
                
                    echo 'Code deployed to Production.'
                }

              
            
        }


    }
}
