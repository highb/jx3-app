pipeline {
    agent { docker { image 'ruby' } }
    stages {
        stage('build') {
            steps {
                sh 'echo this should do something'
                sh 'ruby --version'
            }
        }
    }
}
