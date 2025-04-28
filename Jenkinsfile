pipeline {
    agent any
    {
        
    }
	
	tools {
		jdk 'jdk17'
		maven 'maven3.9'
	}

    node('SlaveNode') {
		stages {
			stage('Package') {
				steps {
					sh 'mvn package'
				}
			}
		}
    }
    
}
