pipeline {
  agent any
  tools {
    // Define Maven tool installation
    maven 'Maven'
  }
  stages {
    stage("SCM Checkout") {
      steps {
        // Checkout source code from Git repository
        git 'https://github.com/1234shaik/thymeleafexamples-petclinic.git'
      }
    }
    stage('Maven Build') {
      steps {
        // Use Maven tool to run 'mvn install'
        bat 'mvn install'
      }
    }
  }
}
