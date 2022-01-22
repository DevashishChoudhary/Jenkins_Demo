pipeline {
    agent any
    
    tools {
        maven 'Maven_3_8_4'
    }

    stages {
        stage('Compile') {
            steps {
                    sh 'mvn clean compile'
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
