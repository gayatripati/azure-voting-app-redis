pipeline {
    agent any
    stages {
      stage('verify branch') {
        steps {
          echo "$GIT_BRANCH"
        }
      }  
      stage('docker build') {
        steps {
          sh(script: 'docker compose build')
      }
    }
  }
}    
        
          
