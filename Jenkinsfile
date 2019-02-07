stage('GIT CHECKOUT'){
  git 'https://github.com/octopent/my-app'
  }
        
stage('COMPILATION'){
  // Get maven home path
  def mvnHome =  tool name: 'jenkins_maven', type: 'maven'   
  sh "${mvnHome}/bin/mvn package"
  }
