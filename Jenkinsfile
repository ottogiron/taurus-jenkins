pipeline {
    agent { dockerfile true }
    stages {
        stage('Test') {
            steps {
                bzt "test/quick_test.yml"
            }
        }
    }
}
