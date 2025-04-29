pipeline {
    agent any
    
    tools {
        jdk 'jdk17'
        maven 'maven3.9'
    }
    stages {
        stage('Test') {
            steps {
               sh 'mvn test'
            }
        }
        stage('Package') {
            steps {
                sh 'mvn -DskipTests=true package'
            }
        }
    }
}
