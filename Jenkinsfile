pipeline {
    agent any

      environment { 
        ENV_URL  = "pipeline.learning.com"             // Declaring pipeline at Pipeline level
        //SSH_CREDENTIALS = credentials('SSH_CRED') 
    }
    stages {
        stage('Stage Name 1') {
            steps {
                sh "echo Hello World $ENV_URL"
            }
        }
        stage('Stage Name 2') {
            steps {
               sh "echo Hello World Shahid"
            }
        }
        stage('Stage Name 3') {
            steps {
                sh "echo Hello World Islam"
            }
        }
    }
}