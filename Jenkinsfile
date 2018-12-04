pipeline {
    agent { docker { image 'python:3.5.1' } }
    stages {
        stage('build') {
            steps {
                sh 'python3 --version'
		sh 'echo "Hello World!"'
		sh '''
			echo "Multiline shell steops works too"
			ls -lah
		'''
            }
        }
    }
}


