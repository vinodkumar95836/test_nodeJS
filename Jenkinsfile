pipeline { 
  
   agent any

   stages {
   
     stage('Install Dependencies') { 
        steps { 
           bat 'docker --version' 
        }
     }
     
     stage('Test') { 
        steps { 
           bat 'java --version'
        }
      }

         stage("Deploy application") { 
         steps { 
           bat 'echo 'deploying application'
         }

     }
  
   	}

   }
