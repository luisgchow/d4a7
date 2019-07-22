pipeline {
	agent any	
	stages {
		stage('Initial setup'){
			steps{

				sh 'echo starting'
			     }
				      }
                
                stage('Checking Docker'){
			steps{
				sh 'sudo docker ps'


	      				 }

		             }	

		stage('Build'){
			steps{
				sh 'sudo docker build --tag=php540 .'
			     }


				}



		}
	}
















