pipeline {
  triigers {
    pollSCM('*/2 * * * *')
  }
  when {
  branch 'master'
  }
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
