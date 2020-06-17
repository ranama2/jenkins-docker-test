pipeline {
	agent {
		docker {
			image 'python'
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
	}
}
