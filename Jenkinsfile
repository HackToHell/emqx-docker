pipeline {
agent { label "jenkins-maven" }
  stages {
    stage('') {
      steps {
          container('maven') {
            sh "docker build -t testy ."
          }
      }
    }
  }
}
