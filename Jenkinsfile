pipeline {
	agent any
	stages {
		stage('Build') {
			steps {
				sh 'echo "Current path is: $PWD"'
				sh 'ls -la | cat'
				sh 'npm install'
			}
		}
	}
}
