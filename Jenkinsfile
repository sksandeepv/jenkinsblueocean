pipeline {
  agent any
  stages {
    stage('Build') {
      parallel {
        stage('Build') {
          steps {
            echo 'Sandy Build stage for multi'
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
