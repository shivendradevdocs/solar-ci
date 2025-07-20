pipeline{
    agent any
    tools{
        nodejs 'node-24-24-1'
    }
    stages{
        stage('Installing Dependencies'){
            //options {timestamps()}
            
            steps{
                sh 'sleep 10s'
                sh 'npm install --no-audit'
            }
        }
        stage('Installing version'){
            //options {timestamps()}
            
            steps{
                sh 'sleep 10s'
                sh 'npm -v'
            }
        }
  }
}

