peline {
    agent {
        docker {
            image 'node:6-alpine' 
            args '-p 8080:9090' 
        }
    }
    stages {
        stage('Build') { 
            steps {
                sh 'npm install' 
            }
        }
    }
}
