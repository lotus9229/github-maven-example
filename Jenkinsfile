pipeline{
  agent any{
    stage ('clone repo'){
      steps{
        bat "git clone https://github.com/lotus9229/github-maven-example.git"
        bat "mvn clean -f "github-maven-example"
  }
}
