pipeline{
    agent any
      tools{
        jdk '25'
      }
    
    stages{
        stage('checkjava version'){
            steps{
                bat 'java -version'
                
        
            }
        }
        stage('build'){
            steps{
               bat  'gradle clean build'
            }
        }
    }
}