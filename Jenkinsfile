pipeline {
  agent any
  stages {
    stage('Clone Repository') {
      steps {
        script {
          def gitClone = sh(script: 'git clone https://github.com/lucaslemarie/jenkins.git', returnStatus: true)
          if (gitClone != 0) {
            error('Failed to clone repository')
          }
        }

      }
    }

  }
}