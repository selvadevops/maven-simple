node{
  stage('SCM Checkout'){
    git 'https://github.com/selvadevops/maven-simple'
  }
  stage('Compile-package'){
    def javaHome = tool name: 'jdk7', type: 'jdk'
    def mvnHome = tool name: 'maventamil', type: 'maven'   
    sh "${mvnHome}/bin/mvn package"
  }
}  
