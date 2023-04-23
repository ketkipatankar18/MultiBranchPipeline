pipeline{
  agent any
  stages{
    stage('Branch1'){
      when {
          branch "Branch1"
        }
      steps{
        echo 'This is the Branch1 Pipeline'
      }
    }
    stage('Branches'){
      when {
          branch "Branch*"
        }
      steps{
        echo 'This stage shows up in all Branches'
      }
    }
  }
}
