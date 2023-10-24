pipeline {
    agent any  // This means the pipeline will run on any available agent

    stages {
        stage('Build') {
            steps {
                // This step will compile and assemble the application
                sh './gradlew assemble'
            }
        }

        stage('Test') {
            steps {
                // This step will run the tests for the application
                sh './gradlew test'
            }
        }
    }
}
