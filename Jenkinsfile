pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                sh 'echo "Hello World vijesh"'   
                sh './startprogram.sh'
                sh '''
                    echo "Multiline shell steps works too"
                    ls -lah
                '''
            }
        }
    }
}
