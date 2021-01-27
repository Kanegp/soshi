pipeline {

  agent {
    label 'sondaika'
  }
 stages{

  stage('Build Project') {
 //    when {
 //       buildingTag()
 //         }
      steps {
        sh 'returnStdout: true, script: "git tag --sort version:refname | tail -1").trim()'

       script{
          println env.TAG_NAME
        }        }
        }
        }
        }
