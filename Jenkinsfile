pipeline {
  agent any
  stages {
    stage('checkout') {
      steps {
        sh 'git checkout -b NotifTest'
      }
    }

    stage('branch list') {
      steps {
        sh 'git branch -a'
      }
    }

    stage('merge') {
      steps {
        sh ' git merge NotifTest mergetest'
      }
    }

    stage('rebase') {
      steps {
        sh 'git rebase Notiftest rebasetest'
      }
    }

    stage('delete') {
      steps {
        sh '''
git branch -d NotifTest'''
      }
    }

    stage('work response') {
      steps {
        echo 'Sir, Everything done Sir'
      }
    }

  }
}