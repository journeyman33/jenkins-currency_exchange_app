// SCRIPTED
// node {
//		echo "Build"
//		echo "Test"
//		echo "Integration Test"
// }

// DECLARATIVE (new!)
pipeline {
	// agent any
	agent { docker { image 'maven:3.6.3'} }
	stages {
		stage('Build') {
			steps {
				sh "mvn --version"
				echo "Build"
			}
		}
		stage('Test') {
			steps {
				echo "Test"
			}
		}
		stage('Integration Test') {
			steps {
				echo "Integrated Test"
			}
		}		
	}
}