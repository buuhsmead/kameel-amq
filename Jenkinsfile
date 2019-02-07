node('maven') {

  stage('git check-out') {
        checkout scm
        sh "ls -la"
    }

  stage('S2I') {

    sh "mvn fabric8:deploy"

  }


 

}
