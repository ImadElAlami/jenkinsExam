pipeline {
    agent any
    stages {
        stage('TEST') {
            steps {
                git credentialsId: 'git_credentials', url: 'https://github.com/ImadElAlami/jenkinsExam.git'
            }
        }
    }
}
