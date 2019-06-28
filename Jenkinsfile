pipeline {
  agent {      
    label "jenkins-maven"
  }
  stages {
    stage('') {
      steps {
        build(propagate: true, job: 'Test', wait: true)
        sh 'echo "He ll o"'
      }
    }
  }
}
