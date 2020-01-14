pipeline {
    agent {
        docker { image 'praneetmane/git:latest' }
    }
    stages {
        stage('Test') {
            steps {
                sh 'node --version'
            }
        }
    }
}
