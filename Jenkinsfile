pipeline {
    agent {
        docker { run -it image 'kdvolder/mvn-plus-npm' }
    }
    
     stages {
        stage ('Packaging Stage') {
            steps {
               npm -version
            }
        }
     }
   
}
