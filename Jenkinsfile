pipeline {
  agent any
  stages {
    stage('Checkout Code') {
      steps {
        git(url: 'https://github.com/itsmehali/coronatracker', branch: 'master')
      }
    }

    stage('shell') {
      steps {
        sh 'ls -la'
      }
    }

  }
}