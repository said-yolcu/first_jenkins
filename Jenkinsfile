Jenkinsfile (Declarative Pipeline)

/* Requires the Docker Pipeline plugin */
pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                sh 'echo "Hello World"'
                sh '''
                    echo "multiline shell steps work too"
                    ls -lah
                '''
            }
        }

        stage('Test') {
            steps {
                sh 'echo "hey"'
            }
        }
    }
}
