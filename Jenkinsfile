pipeline{
  agent any
  stages{
    stage('If-Then-Else') {
            steps {
                script {
                    if (env.BRANCH_NAME == 'master') {
                        echo 'Hello from master branch'
                    }  
                    else {
                        echo "Hello from env.BRANCH_NAME branch!"
                    }
                    }
            }
    }
    stage('Branch1'){
      steps{
        echo 'This is the Branch1 Pipeline'
      }
    }
    stage('Branches'){
      steps{
        echo 'This stage shows up in all Branches'
      }
    }
  }
}
