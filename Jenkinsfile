pipeline {
  agent any
  stages {
    stage('stage1') {
      steps {
        sh 'echo "this is Ibolas build number: $BUILD_NUMBER for project $DEMO "'
      }
    }

  }
  environment {
    DEMO = '1'
  }
}