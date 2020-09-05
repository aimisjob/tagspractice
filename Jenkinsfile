pipeline{
 agent any
   stages{
     stage('build'){
       when{
         changeRequest()
        }
       steps{
         echo "hello worlds change request"
         }
        }
       }
      }
