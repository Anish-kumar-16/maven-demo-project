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
      stage('Build'){
      steps{
      sh 'mvn clean package'
    }
      }
    }
  }
}
