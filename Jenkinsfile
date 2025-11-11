pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                echo "🔧 Building application..."
            }
        }
        stage('Test') {
            steps {
                echo "🧪 Running tests..."
            }
        }
        stage('Deploy') {
            steps {
                echo "🚀 Deploying application..."
            }
        }
        stage('Notify') {
            steps {
                echo "📢 Sending notifications..."
            }
        }
    }
    post {
        success {
            echo "✅ Pipeline completed successfully!"
        }
        failure {
            echo "❌ Pipeline failed!"
        }
    }
}

