pipeline {
  agent any
   stages {
    stage('Build') {
      steps {
       echo 'Building application....'
      }
    }
     stage('Test') {
      steps {
       echo 'Running test....'
      }
    }
     stage('Run') {
      steps {
       echo 'running application...'
        bat 'python app.py'
      }
    }
  }
}
