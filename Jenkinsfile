pipeline {
  agent any
  stages {
    stage('checkout') {
      steps {
        git(url: 'https://github.com/ORG-dev18/aug18CalculatorApps.git', branch: 'master', credentialsId: 'jenkinsgithub')
      }
    }
    stage('build') {
      steps {
        echo 'building my maven web project'
        bat 'mvn clean package'
      }
    }
  }
}