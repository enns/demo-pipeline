pipeline {
    agent {
        node {
            label 'master'
        }
    }

    stages {
        stage('compile') {
            steps {
                sh 'mvn clean install'
            }
        }
    }
}