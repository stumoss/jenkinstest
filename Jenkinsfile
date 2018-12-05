pipeline {
    agent any
    stages {
        stage('Stage 1') {
            steps {
                sh 'sleep 1000'
            }
        }
    }
    post {
        always {
            sh 'sleep 1000'
        }
    }
}
