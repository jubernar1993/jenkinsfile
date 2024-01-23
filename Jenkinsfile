pipeline {
  agent any 
   
  stages{
    stage('development') {
     when {
branch 'main'     
}

 steps{
        sh 'echo this is a test'
      }
    }
  }

}
