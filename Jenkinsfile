pipeline{
 agent any
  stages{
     stage ('build') {
       stage {
         echo 'Running build automation'
         sh './gradlew build --no-daemon'
       archiveArtifacts: 'dist/trainSchedule.zip'
     } 
    }
   }
 }
 
