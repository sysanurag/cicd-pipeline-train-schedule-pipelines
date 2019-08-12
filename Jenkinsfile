pipeline{
  agent any 
    stages{
     stage ('Build'){
      stage{
        echo 'running build automation'
        sh './gredlew build --no-daemon'
        archiveArtifacts artifacts: 'dist/trainSchedule.zip'
      } 
    }
  }
}
