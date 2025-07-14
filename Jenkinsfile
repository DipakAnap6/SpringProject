
pipeline {
    agent any

    stages {
        stage('git add') {
            steps {
                echo 'Git Added'
                
            }
        }
        stage('Compaile') {
            steps {
                echo 'Code Compile'
                bat 'javac HelloWorld.java'
            }
        }
        stage('Run') {
            steps {
                echo 'Code Run'
                bat 'java HelloWorld'
            }
        }
    }
}
