pipeline {
agent { label "jenkins-maven" }
  stages {
    stage('') {
      steps {
          container('maven') {
            sh "ls -lah"
            sh "pwd"
          }
      }
    }
  }
}
