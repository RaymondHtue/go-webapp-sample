pipeline {
    agent any
    tools { go '1.14' }
    environment{
        GO111module='on'
    }
    stages {
        stage('Test') {
            steps {
              git 'git@github.com:RaymondHtue/go-webapp-sample.git'
              sh 'go test ./...'

            }   
        }

    }

}
