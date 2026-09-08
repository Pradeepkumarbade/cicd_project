pipeline{
    agent 
    label 'ubuntu'
      tools{
        jdk '21'
      }
    
    stages{
        stage('checkjava version'){
            steps{
                sh 'java -version'
                
        
            }
        }
        stage('build'){
            steps{
                sh './chmod +x gradlew'
                sh '.gradlew build'
            }
        }
    }
}