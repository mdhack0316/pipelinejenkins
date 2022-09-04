pipeline  {

agent any

stages { 
	stage('SCM') { 
		steps  {  
			git branch: 'main', url: 'https://github.com/mdhack0316/javamavenapp' 
			}
		}

	stage('Build') { 
		steps  { 
				sh 'mvn clean package'
			}
		}
	stage('Test') {
		steps  { 
		echo "Testing The Code"

		}
	}
}

}
