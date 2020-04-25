pipline {
    agent any
    stages {
        stage('Build') {
            steps {
                sh 'echo "Hello World"'
                sh '''
                    echo "Multiline shell stpes works too"
                    ls -lah
                '''
            }
        }
    }
}