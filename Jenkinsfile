pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                sh 'echo "Build Stage"'
                sh '''
                    echo "Multiline shell steps works too for build"
                    ls -lah
                '''
            }
        stage('Deploy') {
            steps {
                sh 'echo "Deploy"'
                sh '''
                    echo "Multiline shell steps works too deploy"
                 
                '''
            }
        }
    }
}
