pipeline {
  agent any
  stages{
    stage("build"){
      steps{
        sh "sudo npm install"
      }
    }

    stage("Deploy"){
      steps{
        sh "sudo npm run start:dev"
      }
    }
  }

}
