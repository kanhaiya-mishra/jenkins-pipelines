pipeline {
    agent any
	stages {
        stage ('S0') {
			steps {
                echo 'Hello S0'
			}         
        }
        stage ('S1') {
			parallel {	
				stage ('S2') {
                    steps {
                        echo 'Hello S2'
                    }         
                }
                stage ('S3') {
                    steps {
                        echo 'Hello S3'
                    }         
                }
                stage ('S4') {
                    steps {
                        echo 'Hello S4'
                    }         
                }
                stage ('S5') {
                    steps {
                        echo 'Hello S5'
                    }         
                }
				
			}
		}
		stage ('S6') {
			steps {
                echo 'Hello S6'
			}         
        }

	}
}