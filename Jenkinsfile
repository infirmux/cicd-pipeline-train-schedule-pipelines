pipeline {
  agent any 
  stages {
    stage ('Build') {
      steps {
        echo "Build automation"
        sh './gradlew build --nod-daemon'
        archiveArtifacts artifacts: 'dist/trainShedule.zip'
      }
    }  
  }
}
