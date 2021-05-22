Pipeline{
  agent any
   stages{
     stage("maven test"){
         steps{
             Sh "maven test"
        }
     }
stage("maven compile"){
         steps{
             Sh "maven compile"
       }
     }
stage("maven deploy"){
         steps{
             Sh "maven deploy"
       }
    }
   }
 }