pipeline {
  agent {
    node {
      label 'slave'
    }

  }
  stages {
    stage('Build') {
      steps {
        echo 'Build'
        sh 'echo \'Build\''
      }
    }

    stage('Deploy') {
      steps {
        sh 'echo \'Deploy\''
      }
    }

  }
}