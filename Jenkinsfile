pipeline {
    agent any

    stages {
        stage('Start') {
            steps {
                echo 'Starting...'
            }
        }
        stage('Build') {
            steps {
                sh 'mvn -B -DskipTests clean package'
            }
        }
    }
}