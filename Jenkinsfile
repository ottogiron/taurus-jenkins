pipeline {
    agent { dockerfile true }
    stages {
        stage('Performance Test') {
            steps {
                sh 'bzt test/quick_test.yml -report'
            }
        }
    }
}
