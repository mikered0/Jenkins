node {
  stage('SCM Checkout') {
    git 'https://github.com/mikered0/Jenkins'
  }
  stage('Compile-Package') {
    sh 'mvn package'  
  }
}
