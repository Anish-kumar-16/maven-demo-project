pipeline{
  agrnt any
  tools{
    maven 'Maven-3.9'
  }
  stages{
    stage('Build'){
      steps{
      sh 'mvn clean package'
    }
    }
  }
}
