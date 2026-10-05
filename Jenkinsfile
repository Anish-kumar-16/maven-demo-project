pipeline{
  agent any
  tools{
    maven 'Maven-3.9'
  }
  stages{
    stage('Test'){
      steps{
        sh 'mvn test'
      }
    }
      stage('Build'){
      steps{
      sh 'mvn clean package'
    }
      }
    stage('Docker image build'){
      steps{
        sh 'docker build -t maven-demon:1.0 .'
      }
    }
    }
  }
