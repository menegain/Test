pipeline {
  agent any
  stages {
    stage('Test') {
      steps {
        echo 'Hello WORLD !'
      }
    }
    stage('Shell script') {
      steps {
        sh 'wp core download --locale=fr_FR --force;'
      }
    }
  }
}