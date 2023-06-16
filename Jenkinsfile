pipeline {
    agent any

    stages {
        stage('checkout') {
            steps {
                echo 'Hello World'
            }
        }
        stage('maven build') {
            steps {
                echo 'build'
            }
        }
         stage('code quailty') {
            steps {
                echo 'quailty'
            }
        }
        stage('updload') {
            steps {
                echo 'uploaded in nexus'
            }
        }
          stage('deploy') {
            steps {
                echo 'deploy to tomcat'
            }
        }
    }
}
