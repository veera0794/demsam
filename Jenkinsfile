pipeline {
    agent any

    stages {
         stage('Execute shell script demo2.sh') {
            steps {
               script{
                sh "chmod +x -R ${env.WORKSPACE}"   
                sh './demo2.sh'
               }
            }
        }
        stage('Execute shell script') {
            steps {
               script{
                sh "chmod +x -R ${env.WORKSPACE}"
                sh './demo.sh'
               }
            }
        }
    }
}
