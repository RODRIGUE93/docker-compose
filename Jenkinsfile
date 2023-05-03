pipeline {
    agent any

    stages{
        stage("create zip file"){
            steps{
                zip docker-composeScript$-{BUILD_NUMBER}.zip *  --exclude Jenkinsfile README.md
            }
        }
        
    }
}