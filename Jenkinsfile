pipeline {
    agent { docker { image 'python:3.6.9' } }
    stages {
        stage('Build') {
            steps {
                sh 'python --version'
            }
        stage("list") {
            steps {
                sh 'echo "Hello World"'
                sh '''
                    echo "Multiline shell steps works too"
                    ls -lah
                '''
            }
        }
        }
    }
}
