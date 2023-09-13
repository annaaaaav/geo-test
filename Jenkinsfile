pipeline{
    agent any 
    stages {
    stage('mavin clean'){
        steps{
            sh 'mvn clean'
        }
    }
    stage('mavin install'){
        steps{
            sh 'mvn install'
        }
    }
     stage('mavin package'){
        steps{
            sh 'mvn package'
        }
    }
    }
}