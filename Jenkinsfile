pipeline {
    agent any
    
    stages {
        stage('Ok') {
            steps {
                echo "Ok"
            }
        }

stage('Deploy') {

 steps { 

  timeout(time: 100, unit: 'SECONDS')

  input('Continue to Deploy?')

  bat 'mvn deploy -DmuleDeploy'

 } 
} 
    }
  
}
