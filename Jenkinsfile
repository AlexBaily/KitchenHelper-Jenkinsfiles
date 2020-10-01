pipeline {
    agent any


    stages {
        stage('CloneRepo') {
            steps {
                script {
                    cleanWs()
                    sh 'mkdir \'./src\''
                    sh 'mkdir \'./bin\''
                    dir ('src'){
                        sh 'git clone https://github.com/AlexBaily/KitchenHelper-backend.git'
                        sh 'echo test'
                        sh 'echo test'    
                    }

                }
            }
        }
    }
}
