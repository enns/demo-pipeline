pipeline {
    agent {
        node {
            label 'master'
        }
    }

    stages {
        stage('compile') {
            steps {
                withMaven(jdk: 'Jdk8', maven: 'Maven3.5') {
                    sh 'mvn clean install'
                }
            }
        }
    }
}