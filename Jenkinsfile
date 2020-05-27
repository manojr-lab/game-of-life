pipeline{
    agent any
    tools{
        jdk 'java-8'
        maven 'maven-3'
    }
    stages{
        stage('Code Build'){
            steps{
                sh 'mvn clean package'
            }
        }
    }
}