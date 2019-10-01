pipeline {
    agent any
    stages {
        stage('One') {
                steps {
                        echo 'Hi all, Welcome to Dev ENV'
			
                }
        }
	    stage('Two'){
		    
		steps {
			input('Do you want to proceed?')
        }
	    }
        stage('Three') {
                     
               
                steps {
			echo "Hi All, Welcome to QA ENV'
		}
	}
        stage('Four') {
		 steps {
			echo "Hi All, Welcome to Prod ENV"
                        }
               
    }
}

