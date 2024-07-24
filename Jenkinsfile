pipeline {
    agent any
    tools {
        maven 'maven3.9'
    }
    stages {
        steps('Build') {
            sh 'mvn -B -DskipTests clean package'
        }
    }
}