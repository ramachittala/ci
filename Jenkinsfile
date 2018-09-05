pipeline {
    agent any
   
    stages {
      stage('Docker Build') {
          steps { 
              sh 'sudo docker build -f nginx.df . -t 10.219.39.124:5000/firstrepo' 
          }
       }

    }

}
