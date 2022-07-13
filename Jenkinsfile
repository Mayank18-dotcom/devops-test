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
                echo 'chenges only to dags'
                sh '''
                    echo nn=${nn}
                '''
            }
        }
    }
}