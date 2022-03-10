pipeline { 
    agent any  
    stages { 
        stage('Testing') {
          steps {
            echo 'running Tests'
            bat 'mvn test'
          }
        }
        stage('Build') { 
            steps { 
               echo 'Building jar files...' 
               bat 'mvn package'
            }
        }
    stage('Deployment')
        {
            steps{
                echo 'Deploying project'
                bat 'mvn deploy'
    }
    
}
    }
}
