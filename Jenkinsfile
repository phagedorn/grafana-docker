pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        sh 'pwd;whoami;./build.sh v5.2.1'
      }
    }
    stage('Start Container') {
      steps {
        sh './start_container.sh'
      }
    }
  }
}