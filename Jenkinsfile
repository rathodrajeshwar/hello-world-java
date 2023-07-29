pipeline{
    agent{
    label 'build-server'
    stages{
       stage{"Git Checkout"}{
          steps{
              https://github.com/rathodrajeshwar/hello-world-java.git
          
          }
       }
       stage{"creation of folder"}{
          steps{
              sh "cd mkdir file1"
         
          }
       }
stage{"Maven Build"}{
          steps{
              sh "mvn clean install"
    
          }
       }
