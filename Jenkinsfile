pipeline {
  agent any
  stages {
    stage('Shell script') {
      steps {
        sh 'wp core download --locale=fr_FR --force;'
      }
    }
  }
}