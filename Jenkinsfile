pipeline {
  agent {      
    dockerfile {
        filename 'Dockerfile'
        label 'my-defined-label'
    }
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
