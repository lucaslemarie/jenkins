pipeline {
  agent any
  stages {
    stage('Test') {
      steps {
        echo 'Start'
        sleep 30
        echo 'stop'
      }
    }

    stage('build') {
      steps {
        echo 'start'
        sleep 30
        echo 'top'
      }
    }

    stage('deploy') {
      steps {
        echo 'start'
        sleep 30
        echo 'stop'
      }
    }

  }
}