pipeline {
  environment {
    registry = "praneetmane/docker-jenkins"
    registryCredential = 'dockerhub'
    dockerImage = 'nginx'
  }
  agent any
    stage('Building image') {
      steps{
        script {
          dockerImage = docker.build registry + ":$BUILD_NUMBER"
        }
      }
    }
