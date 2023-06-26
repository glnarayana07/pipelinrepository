pipeline {
  agent any
  stages {
    stage('develop') {
      steps {
        echo 'hi'
      }
    }

    stage('test') {
      parallel {
        stage('test') {
          steps {
            echo 'bulild stage'
          }
        }

        stage('build') {
          steps {
            echo 'build stage'
            echo 'uildstare'
          }
        }

        stage('deployee') {
          steps {
            echo 'stage deploye'
          }
        }

      }
    }

  }
}