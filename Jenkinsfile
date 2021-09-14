pipeline{
agent any
 stages{
   stage("cleaning stage"){
   step{
   bat "mvn clean"
   }
   }
   stage("Testing stage"){
   step{
    bat "mvn test"
   }
  
   }
   stage("Packaging stage"){
   step{
   bat "mvn package"
   }
   
   }
 }

}