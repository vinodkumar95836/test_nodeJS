pipeline { 
  
   agent any

   stages {
   
     stage('Install Dependencies') { 
        steps { 
           echo 'install success' 
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
