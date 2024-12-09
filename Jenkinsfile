pipeline{
   agent any
   stages{
     stage('Build'){
       steps{
         script{
          bat 'C:\\Windows\\System32\\cmd.exe /c docker build -t getting-started-app .'
         }
       }
     }
     stage('Test'){
       steps{
         script{
          echo 'running tests'
           
         }
       }
     }
     stage('Deploy'){
       steps{
         script{
          echo 'DEploying'
           
         }
       }
     }
   }
}
