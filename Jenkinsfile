pipeline {
    agent any

    stages {
        stage("Validate") {
            steps {
                sh 'date'
                sh 'ls -las'
            }
        }

        stage("Thingy") {
            steps {
                sh 'df -h'
                sh 'ps -ef'
            }
        }
    }
}

// vim:ft=groovy sw=4 ts=4 et
