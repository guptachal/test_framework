pipeline {
    agent any

    stages {
        stage('Build Jar') {
            steps {
                // sh "mvn clean package -DskipTests" // For Unix-based systems
                bat "mvn clean package -DskipTests" // Use this for Windows

            }
        }
    }
}
