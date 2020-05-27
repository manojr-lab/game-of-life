pipeline{
    agent any
    tools{
        jdk 'java-8'
        maven 'maven-3'
    }
    stages{
        stage('Code Build'){
            steps{
                sh 'mvn clean packageclear'
       }
        }
        stage('Docker Build'){
            steps{
                 sh "docker build -t manoj523/GOL-app:${BUILd_NUMBER}"
            }
            
        }
    }
}