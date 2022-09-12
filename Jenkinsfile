pipeline { 
  
   agent any

   stages {
   
     stage('Install Dependencies') { 
        steps { 
           bat 'java --version' 
        }
     }
     
     stage('Test') { 
        steps { 
           bat 'echo "testing application..."'
        }
      }

         stage("Deploy application") { 
         steps { 
           bat 'echo "deploying application..."'
         }

     }
  
   	}

   }
