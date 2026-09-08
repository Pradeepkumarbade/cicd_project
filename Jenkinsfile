pipeline{
    agent any
      tools{
        jdk '21'
      }
    
    stages{
        stage('checkjava version'){
            steps{
                bat 'java -version'
                
        
            }
        }
        stage('build'){
            steps{
               bat 'gradle clean build'
            }
        }
    }
}