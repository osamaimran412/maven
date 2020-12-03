pipeline {

agent any 

tools 
{
  maven "M3"
}
stages 
{
 stage ("Compile") {
   sh "mvn clear compile"
   }
   stage ("Test"){
    sh "mvn clear test"
    }   
    stage ("Deploy"){
    sh "mvn clear install"
    }
 }
}
