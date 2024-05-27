pipeline {
agent any
stages {
	stage('Requirements') {
		steps {
			echo "This is gathering the requirements..."
			sh "python --version"
		}
	}
	stage('Build') {
		steps {
			echo "This is building the packages..."
			echo "Building python virtual env"
		}
	}
	stage('Test') {
		steps {
			echo "This is testing the package..."
		}
	}
	stage('Report') {
		steps {
			echo "This is the report..."
		}
	}
}

}
