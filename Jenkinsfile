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

    stage('Hallo 2 ') {
      steps {
        echo 'Hallo 2'
      }
    }

  }
}