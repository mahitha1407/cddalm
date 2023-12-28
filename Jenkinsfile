pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                script {
                    // Compile and run Java Hello World
                    sh 'javac HelloWorld.java'
                    sh 'java HelloWorld'
                }
            }
        }
    }
}
