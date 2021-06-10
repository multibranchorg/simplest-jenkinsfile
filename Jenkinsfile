  pipeline {
    agent any
    stages {
      stage('Build') {
        steps {
          sh 'echo "Hello World!"'
        }
      }
      stage('Test') {
        steps {
          sh 'echo "Hello Test World!"'
        }
      }
      stage('Deploy') {
        steps {
          sh 'broken'
          sh 'echo "An extra step"'
        }
      }
      
      
    }
  }
