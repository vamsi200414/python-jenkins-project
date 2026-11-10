pipeline {
	agent any
	stages {
		stage('testing') {
			steps {
				sh test -f app.py
			}
		}
		stage('RUN PYTHON APPLICATION') {
			steps {
				python3 app.py
			}
		}
	}
}
