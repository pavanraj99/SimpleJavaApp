pipeline {
    agent any
    tools {
        maven 'Maven 3.9.4'
        jdk 'jdk11'
    }
    stages {
        stage ('Build') {
            steps {
                sh 'mvn clean package' 
	    }
        }
    }
}
