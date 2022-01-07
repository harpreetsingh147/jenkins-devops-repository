//SCRIPTED
//DECLARATIVE
pipeline
{
	agent any
	stages {
		stage('Build')
		{
			steps
			{
				echo 'Build'
			}
		}
		stage('Test')
		{
			steps
			{
				echo 'Test'
			}
		}
		stage('Integration test')
		{
			steps
			{
				echo 'Integration Test'
			}
		}
	} post {
		always {
			echo 'Run always'
		}
		success {
			echo 'Run when build sccess'
		}
		failure {
			echo 'Run when build fails'
		}
	}
}
