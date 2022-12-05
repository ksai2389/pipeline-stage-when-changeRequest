pipeline {
  agent any
  
  stage any {
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
