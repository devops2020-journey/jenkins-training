pipeline{
agent any
 stages{
   stage("cleaning stage"){
   bat "mvn clean"
   }
   stage("Testing stage"){
   bat "mvn test"
   }
   stage("Packaging stage"){
   bat "mvn package"
   }
 }

}