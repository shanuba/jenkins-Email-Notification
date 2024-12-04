pipeline {
    agent any

    stages {
        stage('Execute shell script') {
            steps {
               script{
                sh 'chmod +x script.sh'
                sh './script.sh'
               }
            }
        }
    }
}
