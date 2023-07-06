pipeline{
  agent any

  stages {
    //for each commit
     stage('Lint Checks'){
        steps {
          sh '''
          # ~/node_modules/jslint/bin/jslint.js server.js
           echo Lint Check
           '''
        }
     }
  } //end of stages
}