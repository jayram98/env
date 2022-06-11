pipeline {
    agent any
    stages {
        stage('Example') {
            steps {
                sh '''git checkout dev 
                   git merge origin/feature01'''
            }
        }
    }
    post { 
        always { 
            echo 'I will always say Hello again!'
        }
    }
}
