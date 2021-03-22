pipeline {
  agent any
  stages {
    stage('stage1') {
      steps {
        echo 'This is $BUILD_NUMBER of $DEMO'
      }
    }

  }
  environment {
    DEMO = '1'
  }
}
