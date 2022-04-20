pipeline {
	agent none

	options {
		disableConcurrentBuilds()
		buildDiscarder(logRotator(numToKeepStr: '14'))
	}

	stages {
		stage("test") {
			sh """
               		echo "test Artifact"
               		"""
		}
		stage('Build Code') {
           	steps {
               	sh """
               	echo "Building Artifact"
               	"""
           	}
       	}
}
}
