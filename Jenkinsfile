pipeline {
    agent any
    enviornment{
        ENV_URL=shahid.com
    }
    stages {
        stage('Stage Name 1') {
            steps {
                sh 'echo Hello World $ENV_URL'
            }
        }
        stage('Stage Name 2') {
            steps {
               sh 'echo Hello World Shahid'
            }
        }
        stage('Stage Name 3') {
            steps {
                sh 'echo Hello World Islam'
            }
        }
    }
}