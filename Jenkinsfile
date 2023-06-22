pipeline{
  agent any
  stages{
    stage('Master'){
      steps{
        echo 'This is the Master Branch Pipeline'
      }
    }
    stage('If-Then-Else') {
            steps {
                script {
                    if (env.BRANCH_NAME == 'master') {
                        echo 'Hello from master branch'
                    }  
                    else {
                        echo 'Hello from %BRANCH_NAME% branch!'
                    }
                    }
            }
        }
  }
}
