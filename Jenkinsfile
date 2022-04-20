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
               	echo "Test Artifact stream"
               	"""
           	}
		stage('Build Code') {
           	steps {
               	sh """
               	echo "Building Artifact stream"
               	"""
           	}
       	}
}
}
