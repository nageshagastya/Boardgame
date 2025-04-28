pipeline {
    agent any {
		label "SlaveNode'
	}
    	
	tools {
		jdk 'jdk17'
		maven 'maven3.9'
	}

    stages {
		stage('Package') {
			steps {
				echo "Building project with Maven in Salve Node..."
				sh 'mvn package'
			
			}
		}
    }
}
