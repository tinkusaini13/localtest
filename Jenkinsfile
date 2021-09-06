pipeline {
    agent any
    stages {
        stage('Create Empty Files') {
            steps {
                sh 'touch /test/file{1..10}.txt'
            }
        }
    }
}
