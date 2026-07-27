pipeline
{
  agent any
  stages{
    stage('compile')
    {
      steps
      {
        bat 'javac AddNumbers.java'
      }
    }
    stage('run')
    {
      steps
      {
        bat 'java AddNumbers'
      }
    }
  }
}
