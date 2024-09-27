pipeline{
  agent any{
    triggers{
      githubPush() //Trigger on Github push
    }
    stages{
      stage('Checkout'){
        steps{
          checkout scm //checkout the repository
        }
      }
    }
  }
}
