
def branchn = ''
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
                branchn = env.BRANCH_NAME
                echo branchn
            }
        }
    }
}