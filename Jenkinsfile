pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo "✅ Just a simple build stage running."
                bat 'cat hello.txt'
            }
        }

        stage('Done') {
            steps {
                echo "🎉 Build complete. You can add more here later."
            }
        }
    }
}
