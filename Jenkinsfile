pipeline {
agent any
  stages{
    stage('Checkout'){
      steps{
     checkout([$class: 'GitSCM', branches: [[name: '*/master']], doGenerateSubmoduleConfigurations: false, extensions: [], submoduleCfg: [], userRemoteConfigs: [[credentialsId: 'Github credentials', url: 'https://github.com/595-Vineel/maven_online_code.git']]])
            }               
      }
         }
 }
