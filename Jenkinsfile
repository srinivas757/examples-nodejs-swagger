pipeline {
  agent any
  stages{
    stage("build"){
      steps{
        sh "npm install"
      }
    }

    stage("Deploy"){
      steps{
        sh "npm run start:dev"
      }
    }
  }

}
