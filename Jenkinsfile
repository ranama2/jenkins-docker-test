pipeline {
	agent {
		docker {
			image 'centos'
		}	
	}
	stages {
		stage("check hostname of docker container") {
			steps {
				sh """
					cat /etc/hostname
				"""
			}
		}
	}
}
