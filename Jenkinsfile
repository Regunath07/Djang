pipeline{
  agent any

  triggers{
    githubPush()
  }

  stages{
    stage('checkout'){
      steps{
      //checkout the respository
      checkout scm
      }
    }
  }
}
