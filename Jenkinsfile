
pipeline {
	agent {
		docker {
			image "centos"
			label "generic"
		}	
	}
}
	stages {
		stage{"check hostname of docker container"} {
			steps {
				sh """
					cat /etc/hostname
				"""
			}
		}
	}
