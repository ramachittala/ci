pipeline {
    agent any
   
    stages {
      stage('Docker Build') {
          steps { 
              sh 'sudo docker build -f nginx.df .' 
          }
       }

    }

}
