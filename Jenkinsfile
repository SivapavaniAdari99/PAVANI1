node{
  stage('SCM Checkout'){
    git 'https://github.com/SivapavaniAdari99/PAVANI1/new/main'
  }
  stage('Compile-Package'){
    // Get maven home path
    def mvnHome =  tool name: 'M3', type: 'maven
    sh "${mvnHome}/bin/mvn package"  
  }
        
}      
