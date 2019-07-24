node{
  stage('SCM Checkout'){
    git 'https://github.com/selvadevops/maven-simple'
  }
  stage('Compile-package'){
   sh 'mvn package'
  }
}  
