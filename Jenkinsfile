pipeline {
	agent any

	stages {
	    stage('Checkout') {
	        steps {
				checkout scm			        }
		    }
		stage('Build') {
	        steps {
				sh ('/opt/softwares/apache-maven-3.6.2/bin/mvn install')
	        }
		}
	}
}
