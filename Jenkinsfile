pipeline {
  agent any
  stages {
    stage('bulid') {
      steps {
        sh '''pwd
date'''
      }
    }

    stage('test') {
      parallel {
        stage('test') {
          steps {
            echo 'test'
          }
        }

        stage('') {
          steps {
            echo 'this is a test step'
          }
        }

      }
    }

    stage('deploy') {
      steps {
        echo 'deploy step'
      }
    }

  }
}