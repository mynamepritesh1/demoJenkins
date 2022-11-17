pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Build Application'
            }
        }
         stage('Test') {
            steps {
                echo 'Test Application'
            }
        }
         stage('Deploye') {
            steps {
                echo 'Deploye Application'
            }
        }
    }
    post{
        always{
            emailext body: 'Summary', subject: 'Pipeline Status', to: 'pritesh1272@gmail.com'
        }
    }
    
}
