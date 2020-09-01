pipeline{
 agent any
   stages{
     stage('build'){
       when{
         tag "release-*"
        }
       steps{
         echo "hello worlds building tags"
         }
        }
       }
      }
