pipeline {
  agent {
    docker {
      image 'mysql:latest'
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