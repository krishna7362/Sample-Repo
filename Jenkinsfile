pipeline {
  agent any
  stages {
    stage('checkout') {
      steps {
        git 'https://github.com/krishna7362/Sample-Repo.git'
      }
    }
    stage('build') {
      steps {
        bat 'mvn clean insatll'
      }
    }
  }
}