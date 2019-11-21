node{
  stage('SCM Checkout'){
    git 'https://github.com/rangaraju29139/basicmaven'
  }
  stage('Compile-Package'){
    sh 'mvn package' 
  }
}
