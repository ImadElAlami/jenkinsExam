pipeline {
    agent any
    stages {
        stage('TEST') {
            steps {
                echo 'Hello World'
                git credentialsId: 'git_credentials', url: 'https://github.com/ImadElAlami/jenkinsExam.git'
            }
        }
    }
}
