pipeline {
    agent any

    stages {
        stage('test ') {
            steps {
                echo 'test successfull'
            }
        }
        
        stage('build') {
            steps {
                echo 'Build successfull'
            }
        }
        
        stage('continue ?') {
            input {
                message "should we continue ?"
                ok "we should continue"
                
            }
            steps {
                echo 'Deploy successful'
            }
        }
    }
}
