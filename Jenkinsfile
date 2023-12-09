pipeline {
  agent any
  stages {
    stage('Build') {
      parallel {
        stage('Build') {
          steps {
            echo 'Sandy Build stage for multi'
            echo 'SANDEEP TESTING'
          }
        }

        stage('Documentation') {
          steps {
            echo 'Documenting'
          }
        }

      }
    }

    stage('Deploy') {
      steps {
        echo 'Deploying'
      }
    }

  }
}
