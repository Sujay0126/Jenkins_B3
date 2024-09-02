pipeline{
  agent any
    stages{
      stage('Compile'){
      steps{
        bat 'javac Index.java'

      }
    }
      stage('Run'){
      steps{
        bat 'java Index'

      }
    }
  }
}
