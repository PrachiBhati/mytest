pipeline {
    agent {
        docker {
            image 'alpine:latest'
        }
    }

    stages {
        stage('Hello') {
            steps {
                sh 'echo "Hello World from Docker Agent7!"'
            }
        }
    }
}
