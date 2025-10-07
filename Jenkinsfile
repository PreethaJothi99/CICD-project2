pipeline {
  agent any
  triggers { githubPush() }

  stages {
    stage('Verify Connection') {
      steps {
        echo "✅ Hello Preetha! Your GitHub → Jenkins integration works!"
      }
    }
  }
}

