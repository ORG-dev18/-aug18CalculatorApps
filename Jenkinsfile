pipeline {
  agent any
  stages {
    stage('checkout') {
      steps {
        git(url: 'https://github.com/ORG-dev18/aug18CalculatorApps.git', branch: 'master', credentialsId: 'jenkinsgithub')
      }
    }
  }
}