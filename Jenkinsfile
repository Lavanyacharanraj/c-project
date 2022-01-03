pipeline {
agent any 
  stages { 
    stage('BUILD'){
      steps {
        sh '''
        #!/bin/bash
        echo "This is a first build stage in jenkinsfile"
        '''
  }
}
    stage('TEST1') {
      steps {
        sh 'echo "first test stage in jenkinsfile"'
      }
    }
    stage('TEST2') {
      steps {
        sh 'echo "second test stage in jenkinsfile"'
      }
    }
    stage('deploy') {
      steps {
        sh 'echo "Final DEPLOY stage in jenkinsfile"'
      }
    }
  }
}
