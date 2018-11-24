node{
  stage('SCM Checkout'){
    git 'https://github.com/sachinshinde2512/demo' 
  }
  stage('Maven Clean'){
    def mvnHome = tool name: 'maven', type: 'maven'
    sh "$(mvnHome)/bin/mvn clean"
  }
  stage('Maven Compile'){
    sh "$(mvnHome)/bin/mvn compile"
  }
  stage('Maven Package'){
    sh "$(mvnHome)/bin/mvn package"
  }
}
