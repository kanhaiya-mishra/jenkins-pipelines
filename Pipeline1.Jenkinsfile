pipeline {
    agent any
	stages {
        stage ('S0') {
			stages {	
				stage ('S1') {
					 stages {
						stage ('S2') {
							stages {
								stage ('S3') {
									steps {
										echo 'Hello S3'
									}         
								}		
								stage ('S4') {
									steps {
										echo 'Hello S5'
									}         
								}
							}      
						}		      
        			}
				}
			}
		}
		stage ('S5') {
			steps {
                echo 'Hello S5'
			}         
        }
	}
}