pipeline {
  agent any
  options {
    buildDiscarder logRotator(numToKeepStr: '', artifactNumToKeepStr : '5', daysToKeepStr: '', numToKeepStr: '5')
  }
  stages {
    stage('Hello') {
      steps {
        echo "hello"
      }
    }
  }
}
