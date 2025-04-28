pipeline {
    agent any
    {
        
    }

    node('SlaveNode') {
		tools {
			jdk 'jdk17'
			maven 'maven3.9'
		}

		stages {
			stage('Package') {
				steps {
					sh 'mvn package'
				}
			}
		}
    }
    
}
