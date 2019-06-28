pipeline {
  agent {      
     label "jenkins-go"
  }
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
