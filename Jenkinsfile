pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                sh 'echo "Hello Daddy RJ"'
                sh '''
                    echo "Multiline shell steps works too"
                    ls -lah
                '''
            }
        }
    }
}
