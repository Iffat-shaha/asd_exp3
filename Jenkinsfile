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
        bat '"C:\\Users\\Iffat Anees Shaha\\AppData\\Local\\Programs\\Python\\Python310\\python.exe" app.py'
      }
    }
  }
}
