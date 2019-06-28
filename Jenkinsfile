pipeline {
agent { dockerfile true }
  stages {
    stage('') {
      steps {
          container('maven') {
            sh "mvn deploy"
          }
      }
    }
  }
}
