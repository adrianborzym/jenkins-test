pipeline {
  agent any
  stages {
    stage('STAGE1') {
      steps {
        sh 'echo "Moje demo numer: $DEMO"'
      }
    }

  }
  environment {
    DEMO = '1'
  }
}