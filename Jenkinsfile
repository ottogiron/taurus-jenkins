pipeline {
    agent {
        dockerfile true
    }

    stages {
        stage('Run Tests') {
            steps {
                bzt test/quick_test.yml
            }
        }
    }
}
