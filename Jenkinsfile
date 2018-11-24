node{
  stage('SCM Checkout'){
    git 'https://github.com/sachinshinde2512/demo' 
  }
  stage('Maven Clean'){
    tool name: 'maven', type: 'maven'
    sh 'mvn clean'
  }
  stage('Maven Compile'){
    sh 'mvn compile'
  }
  stage('Maven Package'){
    sh 'mvn package'
  }
}
