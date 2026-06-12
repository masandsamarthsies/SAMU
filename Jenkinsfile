pipeline {
  agent any

  triggers{
    githubPush()
    cron('H/5 * * * *')
  }

  stages {
    stage('Build') {
      steps {
        echo 'Build triggered by Github or cron scehdule'
      }
    }
  }
}
