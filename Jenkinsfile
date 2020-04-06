pipeline {
    agent any
    stages {
        stage('Deploy') {
            when {
                branch 'master'
            }
            steps {
                sh 'echo building on master branch'
                build 'demo-nodejs-deployment/deployment'
            }
        }
    }
}
