pipeline {
  agent any
  stages {
    stage('') {
      steps {
        build(propagate: true, job: 'Test', wait: true)
        sh 'echo "He ll o"'
      }
    }
  }
}
