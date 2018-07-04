pipeline {
    agent { docker { image 'python:3.5.1' } }
    environment {
        PATH = "C:\\Program Files\\Git\\usr\\bin;C:\\Program Files\\Git\\bin;${env.PATH}"
        stages {
            stage('build') {
            steps {
                sh 'python --version'
            }
        }
    }
}
}
