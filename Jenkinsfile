pipeline {
    agent { docker { image 'windows' } }
    stages {
        stage('build') {
            steps {
                sh 'windows --version'
            }
        }
    }
}
