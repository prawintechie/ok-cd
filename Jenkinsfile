pipeline {
    agent {
        docker { image 'kdvolder/mvn-plus-npm' }
    }
    
     stages {
        stage ('Packaging Stage') {
            steps {
               npm -version
            }
        }
     }
   
}
