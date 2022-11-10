node{
  stage('checkout SCM'){
  git branch: 'jenkins_test',url:'https://github.com/benhadjyahia/devopsFront.git'}
  stage(install node module){
  sh'npm install'
  }
  stage(test){
  sh'npm run build --prod'
  }
  
}
