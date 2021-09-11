pipeline {

  agent {
    node {
      // The entire job will run on one specific node
      label 'nonexistent-label'
    }
  }

  stages {
    stage('Test') {
      steps {
        sh "echo hello 4"
      }
    }
  }
}

