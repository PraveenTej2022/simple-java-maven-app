pipeline {
    
    agent none
    
   stages {
        
        stage('Build'){
            
            agent {
                label "Maven-Slave"
            }
          
          steps {
             
                echo "my master branch"
          }
        }
   }
}
