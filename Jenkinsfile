pipeline {
    agent any

    stages {
        stage("build") {
            steps {
                echo 'building the application...'
            }
        }

        stage("test") {
            steps {
                echo 'testing the applications...'
            }
        }

        stage("deploy") {
            stages {
                echo 'deploying the application...'
            }
        }
    }
}