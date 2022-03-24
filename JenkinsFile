pipeline
  {
  agent any
        stages('One'){
        steps{
              echo 'Hii, this is priya sharma'
              }
        }
        stage{'Two'){
            steps{
                input('Do you want to proceed')
                }
        }
        stage('Three') {
        when {
              not {
                  branch "master"
                  }
              }
              steps {
                  echo 'Hello'
                 }
           }
   }
