pipeline {
  agent any
  stages {
    stage('build') {
      steps {
        sh '''pwd
date
git clone https://github.com/ermahen07/pfdepartment.repo.git
ls
mkdir sona
'''
      }
    }

    stage('test') {
      steps {
        echo 'test this project'
      }
    }

    stage('deploy') {
      steps {
        echo 'this is my deployment'
      }
    }

    stage('prod') {
      steps {
        echo 'production'
      }
    }

    stage('f') {
      steps {
        sh 'sleep 30'
      }
    }

  }
}