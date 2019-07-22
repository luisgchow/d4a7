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
				sh 'cp Dockerfile ./'
				sh 'sudo docker build --tag=php540 .'
				sh 'sudo docker login'
				sh 'sudo docker tag php540 lgch/d4a6:v3'
				sh 'sudo docker push lgch/d4a6:v3'
			     }


				}



		}
	}
















