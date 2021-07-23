node{
  stage('SCM Checkout'){
    git 'https://github.com/anilp2005/myapp2021'
    when {
        branch "main"
    }
  }
  stage('Compile-Package'){
    sh 'mvn package'
  }
  
}
