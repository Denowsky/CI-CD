pipeline {
    agent { docker { image 'phyton:3.15.2-alphine3.24' } }
    stages {
        stage('build') {
            steps {
                sh 'python --version'
            }
        }
    }
}