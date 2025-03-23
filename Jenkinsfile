
pipeline {
    agent any
    stages {
        stage('Performance Testing') {
            steps {
                echo 'Running K6 performance tests...'
                sh '/opt/homebrew/bin/k6 run k6.js'
            }
        }
    }
}
