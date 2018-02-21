pipeline {
  agent {
    docker {
      image '5435658a63ac'
    }
    
  }
  stages {
    stage('build') {
      steps {
        git(url: 'https://github.com/nagarjuna8686/pipeline.git', branch: 'master')
      }
    }
    stage('test') {
      steps {
        git(url: 'https://github.com/nagarjuna8686/pipeline.git', branch: 'master')
      }
    }
    stage('deliver') {
      steps {
        git(url: 'https://github.com/nagarjuna8686/pipeline.git', branch: 'master')
      }
    }
  }
}