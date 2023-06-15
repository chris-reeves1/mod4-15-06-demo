pipeline {
    agent any
    stages {
        stage("build directory"){
            steps {
                sh "mkdir ~/jenkins-test"
            }
        }
        stage("add a file"){
            steps {
                sh "touch ~/jenkins-test/file1"
            }
        }
    }
}