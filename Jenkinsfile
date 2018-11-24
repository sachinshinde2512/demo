pipeline{
  agent any
  tools {
    maven 'maven'
  }
  stages {
    stage('SCM Checkout'){
      steps {
        git 'https://github.com/sachinshinde2512/demo'
      }
  }
    stage('Maven Clean'){
      steps {
        sh 'mvn clean'
      }
  }
    stage('Maven Compile'){
      steps {
        sh 'mvn compile'
      }
  }
    stage('Maven Package'){
      steps {
        sh 'mvn package'
      }
  }
 }   
}
