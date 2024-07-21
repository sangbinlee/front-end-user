pipeline {
    agent any
    stages {
        stage('build') {
            steps {
                echo 'building the application...'
                cd "/var/jenkins_home/workspace/Book Management App/src/frontend"
                yarn install
                yarn clean
                yarn build
            }
        }
        stage('test') {
            steps {
                echo 'testing the application...'
            }
        }
        stage('deploy') {
            steps {
                echo 'deploying the application...'
            }
        }
    }
}
