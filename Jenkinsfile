pipeline {
    agent any
triggers {
    pollSCM '* * * * *'
}
    stages {
        stage('Test') {
            steps {
                echo 'This is build stage'
            }
        }
        stage('Build') {
            steps {
                echo 'This is Test stage'
    }
}
        stage('Deploy') {
            steps {
                echo 'This is Deploy stage'
            }
        }
    }
}
