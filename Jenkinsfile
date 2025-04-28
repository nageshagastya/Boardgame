pipeline {
  agent any
  tools{
    maven 'maven3.9'
    jdk 'jdk17'
  }
  stages{
    stage ('package'){
      steps {
        sh 'mvn package'
      }
    }
  }

}
