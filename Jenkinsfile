pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                sh 'echo "Hello Daddy RJ to our success!"'
                sh '''
                    echo "Multiline shell steps works too"
                    cat > hello.txt
	            this is a test
                    done;
                '''
            }
        }
    }
}
