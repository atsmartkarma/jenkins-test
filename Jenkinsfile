pipeline {
  agent any
  stages {
    stage('Test') {
      steps {
        sh '''pwd
ls
gem install bundler
bundle install'''
      }
    }
  }
}