pipeline {
	  agent any
	  stages {
		  stage ('build') {
		  steps {
		  withmaven (maven: 'apache-maven-3.6.1') {
		  sh 'mvn install'
			}	  
			}  
			}
	           }
		}				
