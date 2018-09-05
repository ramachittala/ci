pipeline {
    agent any
   
    stages {
      stage('Docker Build') {
          steps { 
              docker build -f nginx.df 
          }
       }

    }

}
