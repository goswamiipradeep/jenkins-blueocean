pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        sh '''pwd
date ls
touch pradeep'''
      }
    }

    stage('Test') {
      parallel {
        stage('Test') {
          steps {
            echo 'test print'
          }
        }

        stage('test par / Print Message') {
          steps {
            echo 'test par'
          }
        }

      }
    }

  }
}