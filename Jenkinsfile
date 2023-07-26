pipeline {
  agent any
  stages{
    stage("Build"){
      steps{
        echo "Garima Build"
      }
    }
    stage("Test"){
      steps{
        echo "Garima Test"
        sh '''
        python3 gptest.py
        '''
      }
    }
    stage("Deploy"){
      steps{
        echo "Garima Deploy"
      }
    }
  }
}
