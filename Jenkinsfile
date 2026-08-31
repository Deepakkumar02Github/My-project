pipeline
{
agent any;
stages{
stage('GIT '){
steps{
   git credentialsId: '50302996-1c79-4c45-ade0-1631673ed959', url: 'https://github.com/Deepakkumar02Github/My-project.git'
   }
 }
   post{
      success{
         sh 'tar -cvf file.tar C:\ProgramData\Jenkins\.jenkins\workspace\github_pipeline/ '
      }
      failure{
         sh 'date'
      }
      always{
         sh 'ipconfig enp0s3'
      }
   }
 }
}
