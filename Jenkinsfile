pipeline {
  agent any
  tools {
    maven 'jenkins-maven' 
  }
  stages {
    stage ('Build') {
      steps {
        sh 'mvn clean package'
      }
    }
  }
}
