//SCRIPTED
//DECLARATIVE
pipeline {
	agent {docker {image 'maven:3.6.3'}}
	stages {
		stage('Build') {
			steps {
				echo 'Build'
			}
		}
		stage('Test') {
			steps {
				echo 'Test'
			}
		}
		stage('Integration test') {
			steps {
				echo 'Integration Test'
			}
		}
	} 
	post {
		always {
			echo 'run always'
		}
		success {
			echo 'run when build success'
		}
		failure {
			echo 'run when build fails'
		}
	}
}
