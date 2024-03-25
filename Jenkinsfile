pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                git branch: 'main', url: 'https://github.com/vulinhnopro2704/devops-todo-app.git'
            }
        }

        stage('List Files') {
            steps {
                sh 'ls -la'
            }
        }
    }
}