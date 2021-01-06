pipeline {
  agent any 
  stages {
    stage('stage1') {
      steps {
        echo "Hello World again and again!"
      }
    }
    stage('stage2') {
      steps {
        echo "Hello World from stage 2"
      }
    }
  }
  post {
    always {
      echo "This will always run"
    }
  }
}
