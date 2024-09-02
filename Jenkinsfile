pipeline{
  agent any
    stages{
      stage('Compile'){
      steps{
        bat 'javac index.java'

      }
    }
      stage('Run'){
      steps{
        bat 'java index'

      }
    }
  }
}
