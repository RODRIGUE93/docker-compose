pipeline {
    agent any

    stages{
        stage("create zip file"){
            steps{
               sh 'zip docker-composeScript-${BUILD_NUMBER}.zip *  --exclude Jenkinsfile README.md '
            }
        }
        
    }
}