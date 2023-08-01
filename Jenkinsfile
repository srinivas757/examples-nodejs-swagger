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
        sh "sudo pm2 delete"
        sh "sudo pm2 start bin/www"
      }
    }
  }

}
