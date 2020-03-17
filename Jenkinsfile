pipeline {
  agent {
    node {
      label 'TERRAFORM'
    }

  }
  stages {
    stage('One') {
      steps {
        sh '''eho Hello 
echo Bye'''
      }
    }

    stage('Two') {
      steps {
        sh 'echo Nothing'
      }
    }

  }
}