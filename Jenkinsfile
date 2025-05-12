pipeline {
    agent any
    stages {
        stage('build') {
            steps {
                echo "Welcome to TechPro Education IT Bootcamp!"
                sh 'echo second step'
                sh 'echo another step'                
                sh '''
                echo 'Multiline'
                echo 'Example'
                mkdir deneme
                cd deneme
                ls
                pwd
                '''
                sh 'pwd'
                echo 'not using shell'
            }
        }
    }
}
