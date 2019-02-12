node {
  stage('SCM Checlout') {
    git 'https://github.com/rsarneja/registry-server'
  }
  
  stage('Complie-Package') {
    sh 'mvn package -DskipTests=true docker-build:build'
  }
}
