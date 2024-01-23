pipeline {
    agent any
    stages {
        stage('TEST') {
            steps {
                git branch: 'main', credentialsId: 'git_credentials', url: 'https://github.com/ImadElAlami/jenkinsExam'
            }
        }
    }
}
