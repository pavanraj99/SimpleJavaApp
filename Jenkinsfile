pipeline {
	agent any
	environment {
		mavenHome = tool 'jenkins-maven'
	}
	tools {
		jdk 'JDK-11'
	}
	stages {
		stage('Build'){
			steps {
				script {
                 
                    sh "D:/apache-maven-3.9.4/bin/mvn clean install"
                }
			}
		}
		
	}
}
