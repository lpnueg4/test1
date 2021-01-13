pipeline {
  agent any
  stages {
    stage('t1') {
      steps {
        sh '''ip add
pwd
echo 123'''
      }
    }

    stage('t2') {
      steps {
        writeFile(file: 'asd', text: '123')
      }
    }

  }
}