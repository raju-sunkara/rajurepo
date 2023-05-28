pipeline {
  agent any
  stages {
    stage('Build our website') {
      steps {
        echo "This is from Build our website"
        git config --global user.email "raju.sunkara@gmail.com"
        git config --global user.name "raju-sunkara"
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
        sh "scripts/deploy_website.sh"
      }
    }
  }
}
