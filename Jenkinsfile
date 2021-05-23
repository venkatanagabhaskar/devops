pipeline{
  agent any
   stages{
      stage("maven test"){
         steps{
             sh "mvn test"
        }
     }
      stage("maven compile"){
         steps{
             sh "mvn compile"
       }
     }
      stage("maven deploy"){
         steps{
             sh "mvn deploy"
       }
    }
   }
 }
