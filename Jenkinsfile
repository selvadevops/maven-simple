node{
  stage('SCM Checkout'){
    git 'https://github.com/selvadevops/maven-simple'
  }
  stage('Compile-package'){
    def mnHome = tool name: 'maventamil', type: 'maven'   
    sh "${mvnHome}/bin/mvn package"
  }
}  
