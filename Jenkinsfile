
pipeline {
  agent any
  stages {
    stage('Starting ') {
      steps {
        echo 'Starting'
      }
    }

    stage('Shell scripting') {
      steps {
        sh 'echo \'Shell scripting test\''
      }
    }

    stage('Build') {
      steps {
        sh 'mvn -B -DskipTests clean package'
      }
    }

  }
}