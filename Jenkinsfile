pipeline {
  agent any  
  // Here we define the stages which we want our job to perform
   stages {
      //Build using maven
      stage ('Build') {
        steps {
          sh label: '', 
           script: 
           '''
           mvn -f pom.xml clean install
           '''
         } 
     }
}

