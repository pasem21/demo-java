@Library ('shared-library') _
pipeline{
  agent any
  tools{
    maven 'maven3'
  }
  
  stages{
      stage('git clone'){
          steps{
            gitclone('master', 'git-credentials', 'https://github.com/pasem21/demo-java.git')
        }
      }
      stage('build code'){
          steps{
            buildcode()
        }
      }
    }
}
