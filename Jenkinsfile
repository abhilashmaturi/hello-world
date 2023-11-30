pipeline {
  agent any
  stages {
    stage('build') {
      steps {
        echo 'hello world'
      }
    }

    stage('prebuild ') {
      steps {
        build 'mvn build '
      }
    }

  }
}