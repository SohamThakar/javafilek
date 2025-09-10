pipeline {
    agent any
    
    stages {
        stage('clone') {
            steps {
             git branch: 'main', credentialsId: '020766bb-94db-4e05-86cc-5685f7503d1b', url: 'https://github.com/SohamThakar/javafilek.git'
            }
    stage('Compile') {
        steps {
            bat 'Javac HelloWorld.java'
            }
    }
        stage('Run') {
            steps {
                bat 'Java Helloworld'
            }
        }
    }         
}
    
