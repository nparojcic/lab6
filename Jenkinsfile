 pipeline {
  agent any
  stages {
    stage("Build scripts"){
      steps {
        sh "mkdir jenkinsbuild || true"
        sh "touch script1.sh"
        sh "echo 'echo this is script 1 running!' > script1.sh"
        sh "touch script2.sh"
        sh "echo 'echo this is script 2 running!' > script2.sh"
        sh "echo chmod+x script1.sh | echo chmod+x script2.sh"
      }
    }
  }
 }
