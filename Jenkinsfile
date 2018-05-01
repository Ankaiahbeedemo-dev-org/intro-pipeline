pipeline {
  agent {
    label 'jdk9'
  }
  stages {
    stage('Say Hello') {
      steps {
        echo 'Hello World'
        sh 'java -version'
      }
    }
    stage('error') {
      steps {
        echo 'hello universe'
      }
    }
  }
}