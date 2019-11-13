node{
  stage('SCM Checkout'){
    git 'https://github.com/SaiVamsiDutt/BasicMaven'
  }
  stage('Compile-Package'){
    def mvnHome =tool name: 'MAVEN', type: 'maven'
    sh '{mvnHome}/bin/mvn package' 
  }
}
