pipeline {
    agent any
    tools {
        maven "M2_HOME"
    }
    stages {
        stage('GIT') {
            steps {
                git branch: 'main',
                    url: 'https://github.com/Sofiene076/SkiDevOps.git'
            }
        }
        stage('DISPLAY SYSTEM DATE') {
            steps {
                sh 'mvn clean compile'
            }
        }
    }
}