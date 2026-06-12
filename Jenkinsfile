pipeline {
  agent any

  triggers{
    githubPush()
  }

  stages {

    stage('build'){
      steps {
        echo 'Building the application'
      }
    }
    stage('Deploy') {
      steps{
        echo 'Deploying the application'
      }
    }
  }
}
