pipeline {
	agent none

	options {
		disableConcurrentBuilds()
		buildDiscarder(logRotator(numToKeepStr: '14'))
	}

	stages {
		stage('Test Code') {
           	steps {
               	sh """
               	echo "TEST Artifact"
               	"""
           	}
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
