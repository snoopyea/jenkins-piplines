pipeline {
  agent any
  stages {
    stage('build') {
      steps {
        sh 'ls -l'
        echo 'Hello Jenkins.'
      }
    }

    stage('deploy') {
      steps {
        sh 'env'
        echo 'This is deploy step.'
      }
    }

    stage('check') {
      steps {
        echo 'This is check'
      }
    }

  }
}