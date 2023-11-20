pipeline {
    agent any
    tools {
        maven 'jenkins-maven'
        jdk 'JDK-11'
    }
    stages {
        stage ('Build') {
            steps {
                sh 'mvn clean package' 
	    }
        }
    }
}
