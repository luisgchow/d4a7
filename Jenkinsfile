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
				sh 'sudo docker-compoe down'
				sh 'sudo docker image rm php540'
				sh 'sudo docker build --tag=php540 .'
			     }


				}
		stage('docker-compose'){
			steps{
				sh 'sudo docker-compose up -d' 

			     }	


				     }

		}
	}
















