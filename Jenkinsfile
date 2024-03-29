pipeline {
    agent any

    stages {
        stage("first") {
            steps{
                sh "pwd"
                sh "ls"
            }
        }
        stage("second") {
            steps{
                sh "git clone https://github.com/vrk2299/tf_s3_remote_backend "
                sh "ls -R "
            }
        }
        stage("third") {
            steps{
                sh "cat tf_s3_remote_backend/code.tf"
            }
        }

    }
}
