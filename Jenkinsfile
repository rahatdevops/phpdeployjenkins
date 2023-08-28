pipeline {
  agent any {
    lavel "Docker agenet"
  }

  stages {
    stage ('Run Docker Compose') {
      steps{
        sh 'docker-compose up -d'
      }
    }
  }
}
