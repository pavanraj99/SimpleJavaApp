pipeline {
    agent any 
    stages {
        stage('Build'){
			steps {
				sh "clean install -DskipTests"
			}
		}

		stage('Test'){
			steps{
				sh "mvn test"
			}
		}
        stage('Deploy') { 
            steps {
                echo "Deploying" 
            }
        }
    }
}
