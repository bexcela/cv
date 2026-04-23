pipeline {
    agent any

    stages {
        stage('Pull and Check') {
            steps {
                // Jenkins automatically pulls the code into the workspace
                echo 'Code has been pulled automatically by Jenkins.'
                sh 'ls -la' // List files to verify they are there
            }
        }
    }
}
