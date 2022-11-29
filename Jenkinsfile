/* Requires the Docker Pileline plugin */
pipleline {
  agent { docker { image 'maven:3.8.6-openjdk-11-slim' } }
  stages {
    stage('build') {
      steps {
        sh 'mvn --version'
      }
    }
  }
}