pipeline {
    agent any
    parameters {
        choice(name:'Environment',choices:['DEV','UAT','PROD'],description:'')
        string(name:'Enter your name',defaultValue:'TechGeekConnect',description:'')
    }
    stages {
        stage('Build') {
            steps {
                echo 'Build : This is triggered from git event'
            }
        }
        stage('Test') {
            steps {
                echo 'Test : This is triggered from git event'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploy : This is triggered from git event'
            }
        }
    }
}
