pipeline {
    agent any
    tools {
        gradle "gradle"
    }
    stages {
        stage('checkout&build') {
            steps {
                git 'https://github.com/Devops5Apr2021/gradleproject.git'
                sh "gradle build"
            }
        }
    }
}
