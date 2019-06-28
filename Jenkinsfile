pipeline {
  agent {      
     label "jenkins-docker"
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
