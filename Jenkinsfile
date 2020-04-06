pipeline {
    agent any
    stages {
        stage('---clean---') {
            steps {
                bat "mvn clean"
                bat " echo 'Tout le monde en parle'"
            }
        }
        stage('--test--') {
            steps {
                bat "mvn test"
            }
        }
        stage('--package--') {
            steps {
                bat "mvn package"
            }
        }
    }
}
