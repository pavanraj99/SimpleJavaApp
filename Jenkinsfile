pipeline {
    agent any 
    stages {
        stage('Build'){
			steps {
				bat "clean install -DskipTests"
			}
		}

		stage('Test'){
			steps{
				bat "mvn test"
			}
		}
        stage('Deploy') { 
            steps {
                echo "Deploying" 
            }
        }
    }
}
