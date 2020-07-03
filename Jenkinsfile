pipeline {
    agent { dockerfile true }
    stages {
        stage('Test') {
            steps {
                sh 'bzt test/quick_test.yml'
            }
        }
    }
}
