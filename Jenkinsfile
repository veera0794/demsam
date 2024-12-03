pipeline {
    agent any

    stages {
         stage('Execute shell script demo2.sh') {
            steps {
               script{
                sh './demo2.sh'
               }
            }
        }
        stage('Execute shell script') {
            steps {
               script{
                sh './demo.sh'
               }
            }
        }
    }
}
