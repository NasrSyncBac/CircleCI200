pipeline {
    agent any
     tools {
        go 'Go 1.17'
    }
    environment {
        GO111MODULE = 'on'
    }
    stages{
        stage('Test') {
                 steps {
                    sh 'go run main.go'
                 }
            }
        }
}
