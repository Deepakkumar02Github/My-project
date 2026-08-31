pipeline
{
agent any;
stages{
stage('GIT '){
steps{
   git credentialsId: '50302996-1c79-4c45-ade0-1631673ed959', url: 'https://github.com/Deepakkumar02Github/My-project.git'
   }
  }
 }
   post{
      success{
        bat 'tar -cvf file.tar "C:\\ProgramData\\Jenkins\\.jenkins\\workspace\\github_pipeline"'
      }
      failure{
         bat 'date /T'
      }
      always{
         bat 'ipconfig'
      }
   
 }
}
