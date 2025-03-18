@Library ('shared-library') _
pipeline{
  agent any
  
  stages{
    stage{
      steps{
        gitclone('master', 'git-credentials', 'https://github.com/pasem21/demo-java.git')
      }
    }
  }
}
