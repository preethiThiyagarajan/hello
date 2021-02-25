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

  input('Continue to Deploy?')
  bat 'mvn deploy -DmuleDeploy'
 } 
} 
    }
  
}
