pipeline {
  agent any
  stages {
    stage {
      steps {
        echo "Running build automation"
        sh './gradlew build --no-daemon' 
        archiveArtifacts artifacts 'dist/trainSchudule.zip'       
      }
    }
  }
}
