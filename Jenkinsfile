pipeline {
  agent any
  stages {
    stage('GetCode') {
      steps {
        sleep 5
      }
    }
    stage('build') {
      steps {
        sh '/usr/local/apache-maven-3.6.0/bin/mvn clean install -DskipTests'
      }
    }
  }
}