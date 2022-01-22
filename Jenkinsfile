pipeline {
    agent any
    
    tools {
        maven 'Maven 3.8.4'
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
