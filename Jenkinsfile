pipeline {
    agent {
      docker {
        image 'kdvolder/mvn-plus-npm'
      }
    }

    stages {
        stage ('Packaging Stage') {
            steps {
                sh "mvn clean package -f ok-cd/pom.xml"
            }
        }
    }
    post {
      always {
        cleanWs()
      }
    }
}
