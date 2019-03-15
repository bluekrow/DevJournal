pipeline {
  agent any
  stages {
    stage('Step01') {
      steps {
        echo 'Hello Test'
      }
    }
    stage('Step02') {
      agent any
      steps {
        echo '2nd step'
      }
    }
  }
}