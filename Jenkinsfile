pipeline {
    agent any
    tools {
        maven 'Maven-Local'   // Use the Maven name configured in Jenkins
    }
    stages {
        stage('Build') {
            steps {
                script {
                    sh 'mvn clean install'
                }
            }
        }
    }
}
