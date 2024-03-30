pipeline {
  agent any
  stages {
    stage('check out') {
      steps {
        git(url: 'https://github.com/abcijk/maven-samples-A6', branch: 'master')
      }
    }

    stage('run') {
      steps {
        sh 'mvn clean test'
      }
    }

  }
}
