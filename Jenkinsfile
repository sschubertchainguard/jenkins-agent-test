pipeline {
  agent { label 'jenkins-agent' }
  stages {
    stage('Checkout') { steps { checkout scm } }
    stage('Build')    { steps { sh 'echo "hello world!"' } }
  }
}
