pipeline {
    agent any 
    stages {
        stage('...to clone...') { 
            steps {
                sh "mvn clean" 
            }
        }
        stage('to Test') { 
            steps {
                sh "mvn test"
            }
        }
        stage('to Deploy') { 
            steps {
                sh "mvn package" 
           }
        }
    }
}
