pipeline{
    agent any
  
    
    stages{
        stage('checkjava version'){
            steps{
                bat 'java -version'
                bat 'mvn -version'
        
            }
        }
        stage('build'){
            steps{
               bat 'mvn clean install'
            }
        }
    }
}