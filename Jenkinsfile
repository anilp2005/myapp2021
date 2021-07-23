node{
 {stage('SCM Checkout'){
git branch: 'main', credentialsId: 'f36abb55-2a94-40a3-a127-a65eab119922', url: 'https://github.com/anilp2005/myapp2021'
    }

  }
  stage('Compile-Package'){
    sh 'mvn package'
  }
  
}
