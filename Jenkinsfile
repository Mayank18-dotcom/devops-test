def nn = 'ss'

pipeline {
    agent any

    stages {
        stage('gitconnect') {
            steps {
                git url : 'https://github.com/Mayank18-dotcom/devops-test.git'
                echo 'connected to git'
            }
        }
        stage('getbranch'){
            steps {
                script{
                    bat 'd:'
                    bat 'cd STUDY'
                    bat 'git clone https://github.com/Mayank18-dotcom/devops-test.git'
                    echo 'changes only to dags1'
                    echo nn
                }
            }
        }
    }
}