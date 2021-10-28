node {
  stage('SCM Checkout') {
    git 'https://github.com/mikered0/Jenkins'
  }
  stage('Complie-Package') {
    sh 'mvn package'  
  }
}
