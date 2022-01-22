pipeline {
    agent any

    stages {
        stage('Compile') {
            steps {
                withMaven(maven : 'maven_3_8_4') {
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
