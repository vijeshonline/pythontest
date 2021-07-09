pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                sh 'echo "Hello World vijesh"'
                python3 myfile.py
                sh '''
                    echo "Multiline shell steps works too"
                    ls -lah
                '''
            }
        }
    }
}
