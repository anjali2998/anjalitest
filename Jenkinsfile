pipeline {
	agent any
	
	stages {
		stage ('Build') {
			steps{
				echo 'Buliding my first project'
			}
		}
		Stage ('Test') {
			steps{
				echo 'Testing'
			}
		}
		Stage ('Deploy') {
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
