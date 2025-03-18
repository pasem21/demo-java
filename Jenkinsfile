@Library ('shared-library') _
pipeline{
  agent any
  
  stages{
      stage('git clone'){
          steps{
            gitclone('master', 'git-credentials', 'https://github.com/pasem21/demo-java.git')
        }
      }
    }
}
