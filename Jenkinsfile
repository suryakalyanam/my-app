node{
   stage('Scm Checkout')
     git 'https://github.com/suryakalyanam/my-app' 
   }
  stage('Compile-Package'){
     def mvnHome= tool name: 'Maven 3.6.0', type: 'maven'
     sh "${mvnHome}/bin/mvn package"
  }
}
 
    
    
 


 
 

