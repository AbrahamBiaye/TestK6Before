
pipeline {
    agent any
    triggers {
    pollSCM('* * * * *')  // Vérifie les mises à jour chaque minute
}
    stages {
        stage('Performance Testing') {
            steps {
                echo 'Running K6 performance tests...'
                sh '/usr/local/bin/k6 run k6.js'
            }
        }
    }
}
