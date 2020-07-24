pipeline{
    agent any
    
    stages{
        stage("Code"){
            steps {
                sh 'javac HelloWorld.java'
                sh 'java HelloWorld'
            }
        }
    }
}
