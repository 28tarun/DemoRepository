pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        bat 'mvn clean package'
        echo 'build completed'
      }
    }
    stage('Test') {
      steps {
        echo 'Test Will be done here'
      }
    }
    stage('Deploy') {
      steps {
        echo 'Deployment will be done here'
      }
    }
  }
  environment {
    JAVA_HOME = 'C:\\Program Files\\Java\\jdk1.8.0_171'
    MAVAN_HOME = 'C:\\apache-maven-3.5.3'
  }
}