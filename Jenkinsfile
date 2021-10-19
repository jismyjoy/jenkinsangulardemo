pipeline {

  tools {
    nodejs 'Node16'
  }
    agent any
    stages {
        stage('Check version') {
            steps {
                echo 'Cleaning..'
               
            }
        }
        stage('Install dependencies') {
            steps {
                echo 'Install deps..'
                bat 'npm install'
            }
        }
        
        stage('Package') {
            steps {
                echo 'npm run build'
            }
        }        
        }
    }
}
