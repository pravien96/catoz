pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                echo 'Hello World'
            }
        }
        stage('Create File') {
            steps {
                sh "touch file1.txt"
            }
        }
    }
}
