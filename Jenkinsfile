pipeline {
	agent {
		dockerfile {
			label 'generic'
		}
	}
	stages {
		stage("run helloworld") {
			steps {
				sh """
					python helloworld.py
				"""
			}
		}
		stage("test request") {
			steps {
				sh """
					python requestgoogle.py
				"""
			}
		}
	}
}
