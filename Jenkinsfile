node{
  stage('SCM Checkout'){
    git 'https://github.com/SaiVamsiDutt/BasicMaven'
  }
  stage('Compile-Package'){
    sh 'mvn package' 
  }
}
