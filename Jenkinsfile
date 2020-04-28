pipeline {
  agent any
  stages {
    stage('Upload to AWS') {
      steps {
        sh 'echo "Hello Wolrd"'
        sh '''
          echo "Multiline shell steps works too"
          ls -lah
          '''
      }
    }
  }
}
