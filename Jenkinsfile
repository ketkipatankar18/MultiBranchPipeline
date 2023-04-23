pipeline{
  agent any
  stages{
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
