pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                // Make the script executable
                sh 'chmod +x build.sh'
                
                // Execute the script
                sh 'sh build.sh'
            }
        }
        stage('Test') {
            steps {
                // Make the script executable
                sh 'chmod +x test.sh'
                
                // Execute the script
                sh './test.sh'
            }
        }
        stage('Deploy') {
            steps {
                // Make the script executable
                sh 'chmod +x deploy.sh'
                
                // Execute the script
                sh './deploy.sh'
            }
        }
    }
}
