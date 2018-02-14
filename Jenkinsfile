pipeline {
  agent any
  stages {
    stage('Shell script') {
      steps {
        sh '''cd /var/www/html;
mkdir jenkins_wp;
cd /var/www/html/jenkins_wp;
wp core download --locale=fr_FR --force;'''
      }
    }
  }
}