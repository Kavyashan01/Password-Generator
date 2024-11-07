pipeline {
    agent any

    stages {
        stage('checkout') {
            steps {
                checkout scmGit(branches: [[name: '*/master']], extensions: [], userRemoteConfigs: [[credentialsId: 'jenkins_token', url: 'https://github.com/Kavyashan01/Password-Generator.git']])
            }
        }
    }
}
