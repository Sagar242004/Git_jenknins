pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                sh 'javac Student.java'
            }
        }

        stage('Run') {
            steps {
                sh 'java Student'
            }
        }
    }
}
