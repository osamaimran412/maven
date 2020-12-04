pipeline {

agent any 

tools 
{
  maven "M3"
}
stages 
{
 stage ('Compile') {
    git 'https://github.com/osamaimran412/maven.git'
   sh "mvn clear compile"
   }
   stage ('Test'){
     git 'https://github.com/osamaimran412/maven.git'
    sh "mvn clear test"
    }   
    stage ('Deploy'){
    git 'https://github.com/osamaimran412/maven.git'  
    sh "mvn clear install"
    }
 }
}
