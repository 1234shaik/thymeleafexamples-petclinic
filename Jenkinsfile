pipeline {
  agent any
  stages {
    stage("scm") {
      steps {
        git 'https://github.com/1234shaik/thymeleafexamples-petclinic.git'
      }
    }
    stage('mvn-install') {
      steps {
        bat 'mvn install'
      }
    }
  }
}
