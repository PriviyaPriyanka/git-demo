pipeline {
	agent any

	stages{
		stage('Checkout') {
			steps {
				echo 'Code checked out'
			}
		}
		stage('Build') {
			steps {
				sh 'exit 1'
			}
		}
		stage('Test') {
			steps {
				echo 'Test stage running'
			}
		}
		stage('Deploy') {
			steps {
				echo 'Deploy stage running'
			}
		}
	}
}
