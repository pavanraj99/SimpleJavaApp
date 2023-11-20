pipeline {
	agent any
	environment {
		mavenHome = tool 'jenkins-maven'
	}
	tools {
		jdk 'JDK-11'
	}
	stages {
		stage('Build') {
            steps {
                // Build the Maven project and package it into a JAR
                script {
                    
                    sh "${mavenHome}/bin/mvn clean package"
                }
            }
        }
		
	}
}
