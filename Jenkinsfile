pipeline {
  agent none
  stages {
    stage('Back-end') {
      agent {
        docker { image 'maven:3.8.1-adoptopenjdk-11' }
      }
      steps {
        sh 'mvn --version'
        echo "clone github repo"
        sh 'git branch: 'main', url: "https://github.com/Prajwal66/python_web_app/"
      }
    }
  }
}
