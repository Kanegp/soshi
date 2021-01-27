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
        sh "git tag --sort version:refname > tags.tmp"
        sh "tail tags.tmp -n 1 > version.tmp"
        sh "cat version.tmp"

       script{
          println env.TAG_NAME
        }        }
        }
        }
        }
