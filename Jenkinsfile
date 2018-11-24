pipeline{
  agent any
  tools {
    maven 'maven'
  }
  stages {
    stage('SCM Checkout'){
      git 'https://github.com/sachinshinde2512/demo' 
  }
    stage('Maven Clean'){
      sh 'mvn clean'
  }
    stage('Maven Compile'){
      sh 'mvn compile'
  }
    stage('Maven Package'){
      sh 'mvn package'
  }
 }   
}
