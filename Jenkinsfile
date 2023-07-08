pipeline {
  agent any
    stages {
        stage('Pull') {
             steps{
                script{
                    checkout([$class: 'GitSCM', branches: [[name: '*/master']],
                        userRemoteConfigs: [[
                            credentialsId: '471007ac-e3ee-4210-9bf9-1a46f8e391b9',
                            url: 'https://github.com/haifgh/Myapp.git']]])
                }
            }
        }
        }
        }
