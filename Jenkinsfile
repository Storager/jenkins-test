pipeline {
    agent {label 'ssh'}

    stages {
        stage('Checkout') {
            steps {
                scm checkout
            }
        }
        stage('Hello') {
            steps {
                echo 'Hello World'
            }
        }
    }
}
