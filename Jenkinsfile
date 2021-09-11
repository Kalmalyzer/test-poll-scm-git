pipeline {

  agent {
    node {
      // The entire job will run on one specific node
      label 'build-game-linux-git-dynamic'
    }
  }

  stages {
    stage('Test') {
      steps {
        sh "echo hello 6"
      }
    }
  }
}

