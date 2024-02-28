pipeline {
    agent any 
    stages {
        stage('Pull') { 
            steps {
                git branch: 'main', url: 'https://github.com/Surajchavan123/jenkins.git' 
            }
        }
        stage('Build') { 
            steps {
                echo "build success" 
            }
        }
        stage('Test') { 
            steps {
                echo "test success" 
            }
        }
        stage('Deploy') { 
            steps {
                echo "deploy success" 
            }
        }
    }
}