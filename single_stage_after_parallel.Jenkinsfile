pipeline {
	agent any
	stages {
		stage ('Deploy'){
			parallel {
            	stage('Deploy-Unix') {
            	    steps {
						echo 'Deploying to Unix'
                 	}
            	}
          	}
        }
	} 
}
