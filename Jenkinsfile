pipeline {
  agent any
  stages {
    stage('Test') {
      steps {
        sh '''pwd
ls
sudo gem install bundler
bundle install'''
      }
    }
  }
}