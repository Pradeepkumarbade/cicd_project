pipeline{
    agent any
    tools{
        jdk 'jdk8'
        maven 'maven3'
    }
    stages{
        stage('checkjava version'){
            steps{
                bat 'java -version'
            }
        }
        stage('build'){
            steps{
               bat 'mvn clean install'
            }
        }
    }
}