pipeline{
  agent any 
  stages{
    stage('Master'){
      when{
        branch = 'master'
      }
      step{
        echo 'Deploying master branch code'
      }
    }
    stage('Dev'){
      when{
        branch = 'dev'
      }
      step{
        echo 'Deploying dev branch code'
      }
    }
  }
}
