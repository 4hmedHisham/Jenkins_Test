pipeline {
  agent any
  stages{
      stage("build"){
        steps {
          echo 'Building the Code...'
          gcc HelloWorld.c -o HelloWorld_exe
      }
    }
    stage("TEST"){
        steps {
          echo 'Testing the Code_FAKE...'
          gcc HelloWorld.c.c -o HelloWorld_exe
      }
    }
    stage("DEPLOY"){
        steps {
          echo 'Deploying the Code_FAKE...'
          
      }
    }
  }
}
