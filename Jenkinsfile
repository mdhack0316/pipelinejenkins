pipeline  {

agent any 

stages { 
	stage('SCM') { 
		steps  {  
			git branch: 'main', url: 'https://github.com/mdhack0316/javamavenapp' 
			}
		}

	stage('Deploy') { 
		steps  { 
				echo "Deploying The Code"
			}
		}
	stage('Test') {
		steps  { 
		echo "Testing The Code"

		}
	}
}

}
