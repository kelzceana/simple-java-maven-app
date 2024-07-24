pipeline {
    agent any
    tools {
        maven 'maven3.9'
    }
    stages {
        stage('Build') {
            sh 'mvn -B -DskipTests clean package'
        }
    }
}