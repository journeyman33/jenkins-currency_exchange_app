// SCRIPTED
// node {
//		echo "Build"
//		echo "Test"
//		echo "Integration Test"
// }

// DECLARATIVE (new!)
pipeline {
	agent any
	stages {
		stage('Build') {
			steps {
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