pipeline {
    agent any

    tools {
        // Install the Maven version configured as "M3" and add it to the path.
        maven "jenkins-maven"
    }

    stages {
        stage('Build') {
            steps {
                // Get some code from a GitHub repository
                git 'https://github.com/pavanraj99/SimpleJavaApp.git'
                // To run Maven on a Windows agent, use
                bat "mvn clean package"
            }
        }
    }
}
