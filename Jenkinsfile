pipeline{
    agent{
    label 'build-server'
    stages{
       stage{"Git Checkout"}{
          steps{
              https://github.com/rathodrajeshwar/hello-world-java.git
         
          }
       }
stage{"Maven Build"}{
          steps{
              sh "mvn clean install"
    
          }
       }
