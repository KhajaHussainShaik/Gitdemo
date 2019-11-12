pipeline {
  agent {
    docker {
      image 'maven'
    }

  }
  stages {
    stage('Test') {
      steps {
        sh 'echo "Hello world"'
      }
    }
  }
}