pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        echo 'Compilation...'
      }
    }
    stage('Test') {
      steps {
        echo 'Tests...'
      }
    }
    stage('Deploy') {
      steps {
        echo 'Affichage de contenu de index.js'
        sh 'cat index.js'
      }
    }
  }
}