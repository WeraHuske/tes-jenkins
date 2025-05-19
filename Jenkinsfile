pipeline {
  agent any

  stages {
    stage('Preparation') {
      steps {
        echo 'Menyiapkan pipeline...'
      }
    }

    stage('Build') {
      steps {
        echo 'Proses build berjalan...'
      }
    }

    stage('Test') {
      steps {
        echo 'Menjalankan pengujian...'
      }
    }

    stage('Deploy') {
      steps {
        echo 'Deploy ke Minikube (simulasi)...'
      }
    }
  }
}
