pipeline {
  agent any
  stages {
    stage('Build our website') {
      steps {
        echo "This is from Build our website"
        sh "java -jar HelloWorld.jar"
      }
    }

    stage('Run unit tests') {
      steps {
        echo "Run Unit Tests"
        sh "java -jar HelloWorld.jar"
      }
    }

    stage('Deloy website') {
      steps {
        echo "add scripts to deploy here"
      }
    }
  }
}
