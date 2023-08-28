pipeline {
  agent any {
    level "Docker agenet"
  }

  stages {
    stage ('Run Docker Compose') {
      steps{
        sh 'docker-compose up -d'
      }
    }
  }
}
