pipeline {
    agent { label 'master' }
    stages {
        stage('build') {
            steps {
                sh 'echo step1'
                sh 'echo step2'
                sh '''
                    echo 'Multiline'
                    echo 'Example'
                '''
                echo 'not using shell'
            }
        }
        stage('run') {
            steps {
                sh  'echo st1 '
            }
            
       }
    }
}
