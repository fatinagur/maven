#!groovy

node {
  stage ('Checkout') {
    checkout 'https://github.com/fatinagur/maven.git'
  }

  stage('Compile-Package'){
    sh 'mvn package'
  }
  
}
