pipeline {
  agent any
  stages {
    stage('Shell script') {
      steps {
        sh '''echo -e "Host de la base de donn�e : ";
read dbhost;

echo $dbhost;
wp core download --locale=fr_FR --force;'''
      }
    }
  }
}