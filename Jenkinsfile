pipeline {
	agent any
	
	stages {
		stage('Build') {
			steps{
				echo 'Buliding my first project'
			}
		}
		stage('Test') {
			steps{
				echo 'Testing'
			}
		}
		stage('Deploy') {
			steps{
				echo 'deploying'
			}
		}
	}
	post{
		always {
			echo 'if failed or pass print result'
		}
		success {
			echo 'build is successfull'
		}
		failure {
			echo 'Build failed'
		}
	}
}
