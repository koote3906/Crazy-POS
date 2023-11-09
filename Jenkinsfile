pipeline {
  agent any
  stages {
    stage('Hallo') {
      parallel {
        stage('Hallo') {
          steps {
            echo 'Welcome'
          }
        }

        stage('Checking') {
          steps {
            echo 'Trying Again'
          }
        }

      }
    }

  }
}