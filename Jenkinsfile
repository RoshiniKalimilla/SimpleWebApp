pipeline {
  agent any
  stages {
    stage('Dev') {
      parallel {
        stage('Dev') {
          steps {
            echo 'Development message'
          }
        }

        stage('Test') {
          steps {
            echo 'Test print'
          }
        }

        stage('Plugin') {
          steps {
            echo 'Plugin'
          }
        }

      }
    }

    stage('QA') {
      steps {
        echo 'Quality message'
      }
    }

    stage('UAT') {
      steps {
        echo 'UAT print'
      }
    }

    stage('Deploy') {
      steps {
        echo 'Deploying'
      }
    }

    stage('Operate') {
      steps {
        echo 'Operate'
      }
    }

  }
}