pipeline{
    agent any
    tools{
        java 'jdk8'
    }
    stages{
        stage('checkjava version'){
            steps{
                bat 'java -version'
            }
        }
        stage('build'){
               bat 'mvn clean build'
        }
    }
}