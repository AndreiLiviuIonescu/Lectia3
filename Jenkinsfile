pipeline {
  agent any
  stages {
    stage('Prepare Env') {
      steps {
        node(label: 'WinOSAgent') {
          echo 'Executed on TestAgent'
          sleep 15
        }

      }
    }

  }
  environment {
    JENKINS_JOB = 'BlueOcean'
  }
}