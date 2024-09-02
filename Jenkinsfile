pipeline {
    agent {label 'ssh'}

    stages {
        stage('Checkout') {
            steps {
                checkout scm
            }
        }
        stage('Hello') {
            steps {
                echo 'Hello World'
            }
        }
    }
}
