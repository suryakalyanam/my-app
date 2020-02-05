node{
   stage('Scm Checkout')
     git 'https://github.com/suryakalyanam/my-app' 
   }
  stage('Compile-Package'){
     def mvnHome= tool name: 'Maven 3.6.0', type: 'maven'
     sh "${mvnHome}/bin/mvn package"
  }
 stage('Email Notification'){
    mail bcc: '', body: '''Hi welcome to  jenkins jobs
Thanks
Narendra
''', cc: '', from: '', replyTo: '', subject: 'jenkins job', to: 'saiphani2410@gmail.com'
 }
}

 
 

