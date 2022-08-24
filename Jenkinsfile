pipeline {
  agent any
  stages {
    stage('Maven Build') {
      steps {
        sh 'echo Jenkinsfile demo'
        sh 'hari'
      }
    }
  }
  post {
  success {
    echo "This is success block..."
  }
  failure {
    echo "This is failure block..."
    }
  }
}
