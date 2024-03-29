# jenkinstesting
pipeline {
    agent any

    stages {
        stage('development') {
            steps {
                echo 'i am in development'
            }
        }
        stage('testig ') {
            steps {
                echo 'i am in testing'
    }
}
        stage('release') {
            steps {
                echo 'i am in release'
            }
        }
    }
}

