pipeline {
    agent { label 'master' }
    stages {
        stage('checking python version') {
            steps {
                bat 'python -v'
            }
        }
        
        stage('REPO Cloning'){
            steps {
                bat 'xcopy /S "*" "C:/xampp1/htdocs/Devops_jenkins" /Y'
            }
        }
        
        stage('Print done'){
            steps{
                echo "Done!'
            }
        }
    }
}
