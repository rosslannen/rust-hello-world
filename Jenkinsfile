pipeline {
    agent { docker { image 'rust' } }
    stages {
        stage('build') {
            steps {
                sh 'cargo --version'
                sh 'cargo build'
            }
        }
    }
}
