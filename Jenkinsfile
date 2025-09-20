pipeline {
  agent any
  stages {
    stage('Build') { steps { bat 'hello.cmd' } }
  }
  post { always { archiveArtifacts artifacts:'run_output.txt' } }
}

