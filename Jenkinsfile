pipeline{
  agent any
  stages{
    stage('Master'){
      when {
          branch "master"
        }
      steps{
        echo 'This is the Master Branch Pipeline'
      }
    }
    stage('Branch1'){
      when {
          branch "Branch1"
        }
      steps{
        echo 'This is the Branch1 Pipeline'
      }
    }
    stage('Branch2'){
      when {
          branch "Branch2"
        }
      steps{
        echo 'This is the Branch2 Pipeline'
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
