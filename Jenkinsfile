pipeline {
  agent any
  
  stages  {
    stage('Build') {
      when{
        changeRequest()
      }
      steps {
        echo 'Hellow World changing request'
      }
    }
  }
}
