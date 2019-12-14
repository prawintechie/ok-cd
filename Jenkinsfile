pipeline {
    agent {
        docker { image 'node:7-alpinexxx' }
    }
    stages {
        stage('Test') {
            steps {
                sh 'node --version'
            }
        }
    }
}
