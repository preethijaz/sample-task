pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
              sh """
                    javac HelloWorld.java
                    java HelloWorld
                 """
            }
        }
        stage('Test') {
            steps {
                echo 'Testing..'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying....'
            }
        }
    }
}
