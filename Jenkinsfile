node{
    stage('SCM Checkout'){
      git 'https://github.com/AbhiVastrad/myapp'
    }
    stage('Compile-Package'){
      sh 'mvn package'
    }
}
